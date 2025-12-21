# Tap Loop

[English](README.md) | [Español](README.es.md)

### Intelligent Automation for Actions on Android

Tap Loop is an advanced Android automation app that allows you to create **configurable action flows**, execute **smart clicks**, manage **loops**, and automate interactions with other apps **without requiring root**.

Designed for advanced users, testing, and repetitive task automation.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Key Features

- Automatic opening and closing of apps  
- Automatic clicks by **text, description, or ID**  
- Smart ad closing  
- Execution of actions in **loops**  
- Full control over time, frequency, and repetitions  
- Chained actions in customizable flows  
- Data persistence even after uninstalling the app  
- Integrated **visual debug** tools  

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🧠 How It Works

Tap Loop works through **sequential actions** executed in order.  
Each action is configurable and can be repeated in a controlled manner.

A typical flow would be:

1. Open an app  
2. Wait a few seconds  
3. Tap a specific button by text or description  
4. Repeat the action in a loop  
5. Close the app  

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ Action Configuration

Each action has the following parameters (in seconds):

1. **Initial Delay**  
   Time to wait before executing the action.  

2. **Repeat Interval**  
   How often the action is repeated.  

3. **Number of Repetitions**  
   How many times the action will run.  

4. **Double Execution per Attempt**  
   Option to execute the action **twice in a row**.  

5. **Second Execution Delay**  
   Time to wait between the first and second execution.  

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📦 How to Get an App’s Package Name

To correctly configure an action for another app:

1. Search for the target app on **Google Play**  
2. Tap **Share**  
3. Copy the link  
4. The **package name** will appear when you paste it  
   (example: `com.example.app`)  

This is the name you should use in Tap Loop.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 💾 Data Saving & Persistence

Tap Loop allows persistent saving of:

- App package names  
- Action field values  
- Complete action lists  
- Configured flows  

📌 **Data remains saved even if the app is uninstalled**.

To save:

1. Tap the **Save** button  
2. Access saved data via the **folder button** or **menu**

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Floating Button (Debug & Control)

Tap Loop includes a **floating button** with advanced options:

### 🔍 Screen Debug

- Performs a **complete dump** of all visible elements  
- Shows:
  - Text  
  - Description  
  - Internal ID  
- Very useful when a button has no visible text  

Example:  text CashoutActivity.NavIconBack

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📄 License

This project is distributed under the **GNU GPL v3 license**.  

Any use, modification, or distribution must comply with the terms of this license.
