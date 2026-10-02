# 🧭 Instructions to Download the Repository and keeping it up to date

Git is an important tool for software engineers. You do not have to use it but it makes it easier to keep your local repository in sync with the repository online.
Follow these steps to download and use the **Risk Analysis** repository using **Git in Anaconda**.

## 1. Open the Anaconda Prompt

**On Windows:**

1. Click the **Start Menu**.  
2. Type **“Anaconda Prompt”**.  
3. Click to open it.

**On macOS or Linux:**

- Open your regular **Terminal**.  
- If Anaconda is installed, you can use it the same way.


## 2. Install Git (if you don’t already have it)

In the Anaconda Prompt, type:

```bash
conda install git
```

## 3. Clone the Repository

Navigate to the folder where you want to save the repository:

```bash
cd path/to/your/folder
```

Then clone it using HTTPS:
```bash
git clone https://github.com/theresa-hefele/risk-analysis.git
```

This will create a folder named risk-analysis with all the project files inside.

## 4. Pull Updates from the Repository

To get the latest changes from the remote repository, go into the repository folder:

```bash
cd risk-analysis
git pull
```

## ✅ Notes

- These instructions are **read-only**: no pushing is needed.  
- Use `git pull` whenever you want to update your local copy with the latest changes.
