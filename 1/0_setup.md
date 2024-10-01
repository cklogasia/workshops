Environment Setup

This guide will walk you through the installation and configuration of Git on **Windows**, **macOS**, and **Linux** using only the command line.

---

## 1. Git Installation

### Windows

1. **Open Command Prompt** or **Git Bash**.
2. **Download and install Git**:
   - Run the following command to download and install Git using Chocolatey (make sure you have Chocolatey installed):

   ```bash
   choco install git
   ```

3. **Verify installation**:

   ```bash
   git --version
   ```
   - You should see something like `git version X.X.X`.

---

### macOS

1. **Open Terminal**.
2. **Install Git via Homebrew** (if you don't have Homebrew, install it with the command below):

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
3. **Install Git**:

   ```bash
   brew install git
   ```

4. **Verify installation**:

   ```bash
   git --version
   ```
   - You should see something like `git version X.X.X`.

5. **Alternative installation via Xcode Command Line Tools**:

   ```bash
   xcode-select --install
   ```

---

### Linux

#### Ubuntu/Debian
1. **Open Terminal**.
2. **Update your package list**:

   ```bash
   sudo apt update
   ```

3. **Install Git**:

   ```bash
   sudo apt install git
   ```

4. **Verify installation**:

   ```bash
   git --version
   ```
   - You should see something like `git version X.X.X`.

#### Fedora
1. **Open Terminal**.
2. **Install Git**:

   ```bash
   sudo dnf install git
   ```

3. **Verify installation**:

   ```bash
   git --version
   ```

#### Arch Linux
1. **Open Terminal**.
2. **Install Git**:

   ```bash
   sudo pacman -S git
   ```

3. **Verify installation**:

   ```bash
   git --version
   ```

---

## 2. Git Configuration

After installation, configure Git with your personal information to associate commits with your identity.

1. **Set your name**:

   ```bash
   git config --global user.name "Your Name"
   ```

2. **Set your email**:

   ```bash
   git config --global user.email "your.email@example.com"
   ```

3. **Verify your configuration**:

   ```bash
   git config --list
   ```

---


