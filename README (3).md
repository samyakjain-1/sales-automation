# Sales Automation

## Introduction

**Sales Automation** is a full-stack web application built to streamline the sales process through lead management, sales tracking, and document handling. It integrates an intuitive frontend with a robust backend, aiming to automate and enhance efficiency across the sales workflow.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Examples](#examples)
- [Troubleshooting](#troubleshooting)
- [Contributors](#contributors)
- [License](#license)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/samyakjain-1/sales-automation.git
   cd sales-automation
   ```

2. **Start the development environment:**
   ```bash
   ./start-dev.sh
   ```
   > **Note:** Make sure you have the proper permissions to execute the script.

## Usage

Once the development environment is running, access the frontend via your browser (likely at `http://localhost:3000` or similar). Use the interface to manage leads, sales data, and documents.

## Features

- 📋 **Lead Management:** Track potential clients and their progression through the sales pipeline.
- 📈 **Sales Tracking:** Monitor ongoing sales activities and performance metrics.
- 📂 **Document Handling:** Upload, store, and reference sales-related documents.
- 🧠 **Automated Workflows:** Minimize manual effort by automating repetitive sales processes.
- 🖥️ **Clean UI:** Modern, responsive frontend for easy navigation and usage.

## Dependencies

### Frontend
- TypeScript
- JavaScript
- HTML/CSS

### Backend
- Python
- Shell scripts

> **Tip:** Check `package.json` and `requirements.txt` (if available) for a complete list of dependencies.

## Configuration

Configuration files are not explicitly defined. It's recommended to:

- Look for environment-specific settings inside `.env` or `config/` directories.
- Review backend and frontend folder structures for setup guidance.

## Documentation

There is no dedicated documentation yet. However, key folders include:

- `backend/`: Core logic and server-side scripts.
- `frontend/`: UI components and frontend application logic.
- `onsite_documents/`: Sample documents such as purchase orders.

## Examples

Explore the `onsite_documents/` folder to view example sales and purchase documents used within the platform.

## Troubleshooting

If you encounter issues:

- Ensure all dependencies are correctly installed.
- Confirm that the `start-dev.sh` script executes without errors.
- Review browser or terminal logs for detailed error messages.
