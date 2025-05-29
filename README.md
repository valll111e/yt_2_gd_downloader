# 📥 YouTube to Google Drive Downloader

This project is a simple, browser-based tool built for **Google Colab** that allows users to download videos from **YouTube** directly into their **Google Drive** account.

It's ideal for educational or personal use where video content needs to be stored or processed for offline viewing or analysis.

---

## 🧰 Features

- 🔗 Paste a YouTube video URL and download it directly to your Drive
- 📁 Google Drive integration using `google.colab` and `google.auth`
- 📹 Downloads the **highest resolution** available
- 🧠 Designed to be beginner-friendly and easily customizable

---

## 🚀 How to Use (Google Colab)

1. **Open the notebook in Google Colab**:
   - [Click here to open in Colab](https://colab.research.google.com/github/valll111e/yt_2_gd_downloader/blob/main/downloader1.0.ipynb)

2. **Mount your Google Drive**:
   - Run the first code cell to mount your Drive.

3. **Paste your YouTube video link**:
   - Run the appropriate cell to input your YouTube URL and start downloading.

4. **Find the video in your Google Drive**:
   - The file will appear in your Drive’s root folder (or your chosen destination).

---

## 🛠 Requirements

Google Colab handles most dependencies, but for reference:

```bash
pytube
google.colab
