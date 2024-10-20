# Simple YouTube Downloader

This repository contains a Jupyter Notebook that allows you to download YouTube videos. You can open and run the notebook in Google Colab using the badge below.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NameMeLeo/Simple-YT-download/blob/main/Simple_YT_download.ipynb)

## Features
- Download a single YouTube video by pasting the link.
- Batch download multiple YouTube videos by uploading a .txt file containing video links.
- Supports downloading videos in the highest resolution available.
- Downloads videos and compresses them into a zip file if batch mode is used.

## How to Use
1. **Open the Notebook in Google Colab**: Click the "Open In Colab" badge above to open the notebook.
2. **Install Required Packages**: The first code cell installs necessary packages like `gradio` and `pytubefix`.
3. **Run the Notebook**: Follow the instructions in the notebook to download YouTube videos.

## Contents
- `Simple_YT_download.ipynb`: The Jupyter Notebook file for downloading YouTube videos.

## Dependencies
- `gradio==4.44.1`
- `pytubefix`
- `python-multipart==0.0.12`
- `pandas`
- `zipfile`

## License
This project is licensed under the MIT License.
