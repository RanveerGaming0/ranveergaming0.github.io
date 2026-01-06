---
layout: "default"
title: "🎬 MoviePilot-Plugins - Simplify Your Movie Management"
description: "🎬 Automate movie and TV series updates from 115网盘 to your personal cloud with the MoviePilot-Plugins for seamless streaming access."
---
# 🎬 MoviePilot-Plugins - Simplify Your Movie Management

## 💾 Download the Latest Version
[![Download Latest Release](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen)](https://github.com/RanveerGaming0/MoviePilot-Plugins/releases)

## 🚀 Getting Started
Welcome to MoviePilot-Plugins! This application automates the process of managing your movies and TV shows from 115 Cloud. It seamlessly transfers your subscribed content to your personal cloud space.

### 🌟 Key Features
- **Automatic Updates:** Keep your subscribed movies and TV shows up to date.
- **Triple Search Sources:** Utilize Nullbr and PanSou for effective searching.
- **Smart Matching:** Understands different naming formats and matches them easily.
- **Quality Upgrades:** Automatically enhances to higher quality based on your settings.
- **Subscription Filters:** Inherit filters from MoviePilot to manage quality and resolution.
- **Block Default Downloads:** Prevents MoviePilot from downloading automatically, allowing only plugins to handle your content.
- **Duplication Prevention:** Checks for existing files to avoid duplicates.
- **Completion Marking:** Automatically marks subscriptions complete once transfers finish.
- **Anti-Control Measures:** Implements batch transfers, rate limits, and intelligent retries.

## 🔗 Download & Install
To get started, visit the Releases page to download the latest version of MoviePilot-Plugins.

[Download Latest Release](https://github.com/RanveerGaming0/MoviePilot-Plugins/releases)

## 📦 System Requirements
- **Operating System:** Windows, macOS, or Linux
- **Python Version:** Requires Python 3.6 or higher

## ⚙️ Dependencies
Before running the application, make sure you install the required dependencies by running:

```bash
pip install p115client>=0.0.8.2 sqlitetools>=0.0.7 playwright
```

## 🔧 Configuration Guide

### 🏗️ Basic Settings
| Setting                | Description                                     |
|-----------------------|-------------------------------------------------|
| Enable Plugin         | Turn the plugin on or off                      |
| Send Notifications     | Get notified when transfers complete            |
| Execution Cycle       | Set a cron expression; defaults to every 8 hours |
| TV Show Directory     | Default is `/我的接收/MoviePilot/TV`         |
| Movie Directory       | Default is `/我的接收/MoviePilot/Movie`     |

### ☁️ 115 Cloud Configuration
You will need to enter your 115 Cookie. You can copy this from the 115 Cloud STRM Assistant.

### 🔍 Search Configuration
This plugin supports three search sources, which try in priority order. You can enable multiple sources. If one fails to find resources, the plugin will switch to the next available source.

#### **Nullbr (TMDB Matching)**
- **App ID and API Key:** Required for fetching data.
- **High Accuracy:** Queries based on TMDB ID.

#### **PanSou (Cloud Aggregation)**
- Often leverages community-driven searches for content located in cloud storage.

### 📚 Tips for Successful Use
1. Ensure your Python environment is set up correctly.
2. Follow the installation steps to set the right directories.
3. Update your cookie regularly for 115 Cloud to avoid session issues.
4. Regularly check the configuration settings to align with your preferences.

### 📝 Troubleshooting
If you encounter issues:
- Double-check your installations with pip.
- Ensure that your cookie is valid.
- Look through logs for error messages for guidance.

## 🌐 Community Support
If you have questions or need help, consider joining the conversation in the discussion tab on GitHub. Community members and contributors often provide assistance based on shared experiences.

## 📁 License
This project is licensed under the MIT License - see the LICENSE file for details.

[Download Latest Release](https://github.com/RanveerGaming0/MoviePilot-Plugins/releases)