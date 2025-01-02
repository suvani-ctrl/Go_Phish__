# Gophish Lab Setup and Usage

This README provides instructions for setting up and using Gophish in a penetration testing lab environment. It includes screenshots for clarity and ease of understanding.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup Instructions](#setup-instructions)
- [Using Gophish](#using-gophish)
  - [Starting the Server](#starting-the-server)
  - [Logging In](#logging-in)
  - [Creating a Landing Page](#creating-a-landing-page)
  - [Setting Up Email Templates](#setting-up-email-templates)
  - [Configuring Sending Profiles](#configuring-sending-profiles)
  - [Adding Users and Groups](#adding-users-and-groups)
  - [Launching a Campaign](#launching-a-campaign)
- [Results and Analysis](#results-and-analysis)

---

## Introduction
Gophish is an open-source phishing framework used for simulating phishing attacks and training users against phishing threats. This guide walks you through the steps of setting up and using Gophish in a controlled environment.

---

## Prerequisites

- A machine running Linux (Kali Linux recommended).
- Gophish downloaded and extracted into the working directory.
- Proper network configurations for hosting campaigns.
- Administrative privileges for required ports.

---

## Setup Instructions
1. Navigate to the Gophish directory:
   ```bash
   cd ~/Documents/Gophish_Lab
   ```
2. Start the Gophish server:
   ```bash
   ./gophish
   ```
   Refer to `starting_the_server.png` for visual guidance.

3. Access the admin panel at:
   ```
   https://127.0.0.1:3333
   ```
   Refer to `Logging_In.png` for the login interface.

---

## Using Gophish

### Starting the Server
- Follow the instructions in `starting_the_server.png` to initialize the Gophish server.

### Logging In
- Access the admin dashboard as shown in `Logging_In.png`.

### Creating a Landing Page
1. Go to the **Landing Pages** section.
2. Design a phishing landing page or import an existing one.
3. Refer to `Landing_Page.png` and `Landing_Page_created.png` for examples.

### Setting Up Email Templates
1. Navigate to the **Email Templates** section.
2. Create or edit email templates for your phishing campaign.
3. See `email_templates.png` for sample configurations.

### Configuring Sending Profiles
1. Go to the **Sending Profiles** section.
2. Add SMTP server details for sending emails.
3. Refer to `sending_profiles.png` for guidance.

### Adding Users and Groups
1. Import or manually add target users in the **Users and Groups** section.
2. Check `user_and_groups.png` for reference.

### Launching a Campaign
1. Combine your configurations into a new phishing campaign under the **Campaigns** section.
2. Monitor email delivery and user interactions.
3. See `email_sent.png` for a snapshot of campaign activity.

---

## Results and Analysis

- Monitor campaign results through the Gophish dashboard.
- Refer to `Dashboard.png` and `sucess.png` for examples of campaign reports.

---

### Notes
- Use this setup in a controlled environment with appropriate permissions.
- For further assistance, visit the [Gophish Documentation](https://getgophish.com/documentation).

---

Happy phishing (ethically)!
