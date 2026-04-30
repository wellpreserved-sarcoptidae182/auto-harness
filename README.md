# 🧩 auto-harness - Build a smarter agent loop

[![Download](https://img.shields.io/badge/Download%20auto-harness-blue?style=for-the-badge)](https://github.com/wellpreserved-sarcoptidae182/auto-harness)

## 🚀 What auto-harness does

auto-harness helps you run an agent, watch where it fails, and improve the setup over time. It is built for people who want to bring their own agent and test it in a repeatable way.

Use it to:

- run an agent in a steady loop
- capture failures for review
- tune the harness around weak spots
- block changes that make results worse
- keep track of runs over time

It is meant for Windows users who want a simple way to get a local agent workflow up and running.

## 💻 Windows setup

Use the link below to visit the download page:

[Download auto-harness](https://github.com/wellpreserved-sarcoptidae182/auto-harness)

After you open the page, look for the latest release or the main project files. If the project includes a Windows app or installer, download it to your computer. If it comes as a zip file, save the file and extract it before you run it.

## 🪟 How to install

Follow these steps on Windows:

1. Open the download link above in your web browser.
2. Find the latest version on the page.
3. Download the Windows file.
4. If Windows asks for approval, choose to keep the file.
5. If the file is a .zip archive, right-click it and choose Extract All.
6. Open the extracted folder.
7. Find the app file and double-click it to start.

If Windows shows a security prompt, choose the option that lets you run the app.

## ⚙️ First-time setup

After you start auto-harness for the first time, you may need to set a few basic options:

- choose the agent you want to test
- point the app to your agent folder or command
- set how long each run should last
- pick where logs and reports should be saved
- choose how many test runs to keep

A simple setup works best at first. You can add more detail after you see your first results.

## 🧠 Main features

### 🧪 Failure mining
auto-harness watches runs for errors, bad outputs, timeouts, and broken steps. It saves those cases so you can review them later.

### 🔧 Harness tuning
You can adjust the test loop to better fit your agent. This helps you find the settings that produce stable runs.

### 📉 Regression checks
The app can compare new runs with older ones and flag cases where results get worse.

### 🗂️ Run records
Each run can create logs, notes, and result files. This gives you a clear trail of what changed.

### 🔁 Repeatable tests
You can run the same setup again and again. That makes it easier to see if a change helped or hurt.

## 🧰 What you need

For a smooth run on Windows, use a machine with:

- Windows 10 or Windows 11
- 8 GB of RAM or more
- 2 GB of free disk space
- internet access for downloads or agent services
- permission to run apps from your user account

If you plan to run larger agents or more test cases, more RAM and disk space can help.

## 📁 Recommended folder setup

Keep your files in one place so they are easy to find:

- `Downloads` for the original file
- a folder like `C:\auto-harness` for the extracted app
- a separate folder for logs
- a separate folder for agent output

This makes it easier to clean up old runs and review results.

## 🛠️ Common first-run tasks

When you open the app, you may want to do these things:

- set the agent path or command
- choose a test task or prompt
- set a maximum run time
- pick an output folder
- run one short test first
- check the log file after the run ends

Start with a small test. That helps you confirm the app works before you use a longer run.

## 📊 What to look for in results

After each run, check for:

- errors or crashes
- repeated failed steps
- long pauses
- incomplete output
- changes in output quality
- tasks that pass one day and fail the next

These signs help you find weak parts in the agent or the harness.

## 🔄 Updating the app

When a newer version appears on the project page:

1. Save your current logs if you need them.
2. Download the new version.
3. Replace the old files or install the new build in a new folder.
4. Run a short test again.
5. Compare the new results with the old ones.

Keeping old logs helps you see what changed.

## 🧩 Troubleshooting

### The app does not open
- Check that the file finished downloading.
- Extract the zip file before you try to run it.
- Right-click the app and try Run as administrator.
- Make sure Windows did not block the file.

### The app opens, but nothing happens
- Check the agent path or command.
- Make sure your agent files are in the right folder.
- Look for a log file and check for the first error line.

### The run stops early
- Increase the time limit.
- Check for missing files.
- Make sure the computer did not sleep.

### Results look wrong
- Run the same test again.
- Compare the new output with the old output.
- Review the failure records for the last run.

## 📌 Tips for better runs

- Keep your first test small
- Change one setting at a time
- Save logs after each run
- Use the same test case when you compare versions
- Keep the output folder on a drive with enough free space
- Avoid closing the app during a run

A steady setup gives you cleaner results.

## 🔐 File safety

Only download the app from the project link above. After download, check the file name and folder before you run it. If your browser or Windows shows a file prompt, review it before you continue.

## 🧭 Where to start next

1. Open the download link
2. Get the latest Windows file
3. Extract it if needed
4. Run the app
5. Set your agent path
6. Start a short test
7. Review the logs