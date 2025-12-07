# 🤖 CodeAssist Development Environment

## 💡 Overview and Prerequisites

### Availability
CodeAssist is designed to operate in various environments, including **macOS** (compatible with both Intel and Apple Silicon), **Linux** (specifically Ubuntu 22.04+), and **Windows** (using the Windows Subsystem for Linux 2 or WSL 2). Before proceeding, please ensure your system meets the specified requirements and that you have established the necessary accounts.

### Minimum Hardware Specifications
For successful operation, your machine must meet or exceed these hardware specifications:

* **RAM:** A minimum of 12 GB is required, though 32 GB is strongly recommended for optimal performance.
* **Processor:** A single core CPU is required.
* **Storage:** Ensure at least 10 GB of free space is available for application overhead.
* **Main CPU:** A modern multi-core processor (Intel, AMD, or Apple Silicon) is necessary.

### Required Software Dependencies
The following software tools must be installed prior to setup:

* **Docker:** Latest stable version.
* **Python:** Version 3.10 or newer.
* **Homebrew:** Version 4 or greater (specifically required for macOS installations).
* **Git:** Version 2 or newer (essential for cloning the repository).

### Account Setup and Access
You will need two external accounts to fully utilize and contribute to the platform:

* **Hugging Face:** You must generate a **Write-access API token** to successfully upload your trained models. Refer to the official Hugging Face Guide for token creation instructions.
* **Gensyn Testnet:** Your testnet account will be **automatically created** upon your initial login via your web browser during the setup process.

***

## ⚡️ Rapid Deployment (Quickstart)

If you are using an Integrated Development Environment (IDE) like Cursor, it is recommended to use the provided IDE link to prevent initial setup problems.

### 1. Execute Installation Sequence
Run the following three commands in your terminal to clone the repository and initialize the application:

```bash
git clone [https://github.com/gensyn-ai/codeassist](https://github.com/gensyn-ai/codeassist)
cd codeassist
uv run run.py
# CODEASSIST-


2. Verify Application Launch
After the script finishes, open CodeAssist, load any LeetCode problem, and confirm that the container has started successfully.
3. Optional: Dependency Verification
You can check the versions of your installed dependencies with these commands:
