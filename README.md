# AWS Cloud Infrastructure & Automation Utilities

A lightweight suite of AWS cloud automation utilities, telemetry synchronization helpers, and infrastructure state managers designed for Node.js environments.

## 🚀 Overview

This repository provides reusable modules and automated scripts to:
- Monitor and sync AWS CloudWatch metrics and telemetry data.
- Streamline deployment states and health checks across multi-region configurations.
- Provide structured schema validation for serverless payload invocations.

## 📦 Project Structure

```text
aws/
├── config/
│   └── aws-config.json         # AWS telemetry and deployment configuration
├── src/
│   ├── index.js                # Core telemetry orchestrator
│   └── utils/                  # Helper utilities for cloud state management
├── .gitignore
├── package.json
└── README.md
```

## 🛠️ Prerequisites & Setup

Ensure you have Node.js (v18+) installed:

```bash
# Clone the repository
git clone https://github.com/PrathamC0DES/aws.git
cd aws

# Install dependencies
npm install
```

## ⚙️ Configuration

AWS telemetry configurations and region definitions can be customized in `config/aws-config.json`:

```json
{
  "region": "us-east-1",
  "telemetry": {
    "enabled": true,
    "syncInterval": "hourly"
  }
}
```

## 📜 License

This project is licensed under the ISC License.
