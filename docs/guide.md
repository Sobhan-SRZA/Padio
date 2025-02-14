---
title: Setup and Command Guide
nav_order: 1
---

# Padio Setup and Command Guide

Welcome to the Padio guide! This page will walk you through how to set up Padio on your Discord server and explain how to use its various commands to get the most out of your radio experience.

---

## Getting Started

Before you begin using Padio, make sure you have invited the bot to your server. Once Padio is on your server, follow these steps to set it up:

1. **Invite Padio:**  
   Use the invite link provided on our homepage to add Padio to your server.

2. **Run Setup Commands:**  
   Padio requires a few initial setup commands to configure its behavior on your server. The key setup commands are:
   - **Panel Setup:**  
     Use `/setup panel` (or `p!setup panel` if you’re using a message-based command) to create a control panel.  
     This command will:
     - Request permission to access a specific text channel.
     - Send a control message in that channel.
     - Save the channel ID and message ID in the database for future control and management.
     
   - **Prefix Setup:**  
     Use `/setup prefix` (or `p!setup prefix`) to set a custom command prefix for Padio.  
     This allows administrators to define a unique prefix for invoking bot commands. The chosen prefix, along with your server ID, is saved in our database.
     
   - **Language Setup:**  
     Use `/setup language` (or `p!setup language`) to select the bot’s language.  
     Available languages include English, فارسی, Türkçe, 中文, and 日本語. Your choice, along with the language code and server ID, is stored to personalize the bot’s responses.

3. **AFK Mode Activation:**  
   Use the `/afk` command (or `p!afk [channel | id]`) to enable the 24/7 mode for Padio.  
   - When enabled, Padio will continuously remain in the designated voice channel.
   - The bot saves the voice channel ID and server ID in the database, ensuring that it stays active even if the server is idle.

4. **Radio Station Selection:**  
   The last selected radio station (e.g., “Bass Radio” or “Radio Javan”) is automatically saved in the database alongside your server ID.  
   This ensures that Padio can resume playing your preferred station when needed.

---

## Command Overview

Padio’s commands are divided into several categories: **Admin Commands**, **Music Commands**, **Miscellaneous Commands**, and **Owner Commands**. Below is a detailed explanation of each category:

### 1. Admin Commands

These commands allow server administrators to configure Padio.

- **`/setup panel` or `p!setup panel`:**  
  Creates a radio control panel in a specified text channel for quick management of radio playback.
  
- **`/setup prefix` or `p!setup prefix`:**  
  Sets a custom prefix for invoking bot commands. The prefix is saved per server.
  
- **`/setup language` or `p!setup language`:**  
  Changes the bot’s language. Administrators select from available languages, and the choice is stored in the database.

### 2. Music Commands

These commands control radio playback in your voice channels.

- **`/play` or `p!play`:**  
  Begins streaming your chosen radio station in the voice channel.
  
- **`/pause` or `p!pause`:**  
  Temporarily stops the radio playback.
  
- **`/resume` or `p!resume`:**  
  Resumes playback after a pause.
  
- **`/stop` or `p!stop`:**  
  Stops the radio playback and removes Padio from the voice channel.
  
- **`/volume` or `p!volume [1-200]`:**  
  Adjusts the playback volume or shows the current volume level.
  
- **`/afk` or `p!afk [channel | id]`:**  
  Enables AFK mode so that Padio remains active in the voice channel 24/7. This command saves the channel’s ID for persistent connection.

### 3. Miscellaneous Commands

These commands provide additional information and support.

- **`/about` or `p!about`:**  
  Displays information about Padio, including its features and version.
  
- **`/help` or `p!help`:**  
  Lists all available commands and provides brief descriptions of their functionality.
  
- **`/invite` or `p!invite`:**  
  Provides the invite link for adding Padio to other servers.
  
- **`/ping` or `p!ping`:**  
  Displays the current ping, indicating the bot’s responsiveness.
  
- **`/report` or `p!report`:**  
  Lets you report any issues or bugs directly to the development team.

### 4. Owner (Developer) Commands

Reserved for bot developers and server owners to manage and customize Padio further.

- **`p!setactivity` Command:**  
  Temporarily changes the bot’s status (e.g., playing, streaming, listening).
  
- **`p!guilds [id]`:**  
  Displays a list of servers where Padio is currently active.

---

## How Data is Managed

Padio uses a secure database to store all configuration data:
- **Channel and Message IDs:** For the control panel setup.
- **Custom Prefixes & Language Codes:** For personalizing the bot experience on each server.
- **AFK Mode & Radio Station Data:** Ensuring continuous operation and easy resumption of your favorite radio stations.
- **Usage Statistics:** To help improve performance and functionality.

---

## Final Notes

- **Admin Privileges:** Only server administrators can execute setup commands to modify Padio's behavior.
- **Data Security:** All configuration data is stored securely and used solely to improve your experience with Padio.
- **Support:** For any issues or assistance with setup, please refer to our [Support Discord Server](https://discord.gg/AfkuXgCKAQ) or contact the developer directly.

Enjoy the seamless, high-quality radio experience with Padio and customize it to fit your server’s needs!

---

*This guide is subject to updates. Check back regularly for the latest information on commands and setup procedures.*
