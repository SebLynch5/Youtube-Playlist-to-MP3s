# Playlist to MP3 Downloader

A simple Python script (Jupyter Notebook) that downloads videos from a YouTube playlist and converts them into `.mp3` files using `ffmpeg`.

## Features

- Download all videos from a given YouTube playlist.
- Automatically convert each video to `.mp3` using `ffmpeg`.
- Saves files with safe, clean filenames.

## Requirements

- Python 3
- Jupyter Notebook (e.g., run via Anaconda)
- **ffmpeg** must be installed and accessible via command line.

## How to Install `ffmpeg`

To use this script, make sure `ffmpeg` is installed on your machine:

- **Mac (using Homebrew):**
  Follow this guide:
  https://phoenixnap.com/kb/ffmpeg-mac

- **Windows:**
  Follow this guide:
  https://phoenixnap.com/kb/ffmpeg-windows

- **Linux (Ubuntu):**
  https://phoenixnap.com/kb/install-ffmpeg-ubuntu

## Usage
- Open the notebook using Jupyter.

- Run all cells. Paste your playlist URL into the input cell. The .mp3 files will be downloaded and saved in the specified directory.

## Notes
Ensure ffmpeg is properly installed and added to your system's PATH.

The script suppresses most terminal output from ffmpeg for a cleaner notebook experience.
