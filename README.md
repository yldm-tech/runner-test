# GitHub Actions Self-Hosted Runner Test

This repository is used to test the self-hosted macOS runner.

## Runner Information

- **Name**: macmini
- **OS**: macOS
- **Labels**: self-hosted, macOS, X64

## Test Workflow

The `.github/workflows/test.yml` workflow will:
- Display system information
- Show environment variables
- Test Node.js and Python availability
- List repository contents
- Run a simple calculation

## Running the Test

Push to the `main` branch or manually trigger the workflow to test the runner.
