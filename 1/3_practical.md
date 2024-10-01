# Practical Module: Basic Git Commands

In this practical module, you will practice using the basic Git commands that we covered in the previous section. Follow the steps below to get started.

## Step 1: Clone the Workshop Repository

First, you need to clone the workshop repository to your local machine. Open your terminal (macOS/Linux) or Command Prompt/PowerShell (Windows) and run the following command:

```bash
git clone https://github.com/cklogasia/workshops.git
```

## Step 2: Navigate to the Workshops Directory

After cloning the repository, navigate to the `workshops` directory:

```bash
cd workshops
```

## Step 3: Access the First Workshop

Now, move into the directory for the first workshop. Since the first workshop is represented by the integer `1`, run the following command:

```bash
cd 1
```

## Step 4: Go to the Programs Directory

Next, navigate to the `programs` directory, where you will find the scripts to practice with:

```bash
cd programs
```

## Step 5: Practice Using Git Commands

Here’s a step-by-step guide on how to use the Git commands within the `programs` directory:

1. **Check the Status**: See the current state of the repository.
   ```bash
   git status
   ```

2. **Stage Changes**: Add your scripts to the staging area. Use `git add` for individual files or all changes.
   ```bash
   git add <your_script_file>
   # or to add all changes
   git add .
   ```

3. **Commit Changes**: Commit the staged changes with a meaningful message.
   ```bash
   git commit -m "Add initial script for practice"
   ```

4. **Check the Log**: View the commit history to see your recent commits.
   ```bash
   git log
   ```

5. **Make Changes**: Modify or create new scripts in the `programs` directory.

6. **Stage and Commit Again**: Repeat the staging and committing process for your new changes.
   ```bash
   git add .
   git commit -m "Update script in main branch"
   ```

7. **Push Changes**: If you have a remote repository set up, you can push your changes.
   ```bash
   git push origin main
   ```

## Windows Users: Command Line Instructions

If you are using Windows, you can follow the same commands, but ensure you are using Command Prompt or PowerShell. Here’s how to do it:

1. **Open Command Prompt or PowerShell**:
   - Press `Win + R`, type `cmd`, and hit Enter for Command Prompt.
   - Press `Win + X` and select `Windows PowerShell` for PowerShell.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/cklogasia/workshops.git
   ```

3. **Navigate to the Workshops Directory**:
   ```bash
   cd workshops
   ```

4. **Access the First Workshop**:
   ```bash
   cd 1
   ```

5. **Go to the Programs Directory**:
   ```bash
   cd programs
   ```

6. **Practice Using Git Commands**: Follow the same steps as mentioned above for checking status, staging changes, committing, etc.


