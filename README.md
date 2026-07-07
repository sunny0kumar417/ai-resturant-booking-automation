# 🍽️ AI Restaurant Booking Automation (n8n)

## Overview

This project automates restaurant table reservations using an AI-powered workflow built with n8n.

Instead of manually responding to booking requests, the workflow collects customer information, validates availability, stores reservation data, and generates confirmation messages automatically.

---

## Features

* AI-powered booking assistant
* Extracts booking information from customer messages
* Checks table availability
* Saves reservations to Google Sheets
* Sends booking confirmation
* Modular workflow for easy customization

---

## Workflow

1. Customer sends a booking request.
2. AI extracts:

   * Customer name
   * Date
   * Time
   * Number of guests
3. Availability is checked.
4. Reservation is stored.
5. Customer receives confirmation or an alternative time.

---

## Tech Stack

* n8n
* AI Agent
* Google Sheets
* HTTP Requests
* Webhooks

---

## Current Limitation

The final WhatsApp Business integration is not included because it requires a verified WhatsApp Business account. The workflow has been tested using alternative triggers and is ready to connect once credentials are available.

---

## Future Improvements

* WhatsApp Business Cloud API
* Calendar integration
* Email notifications
* CRM integration
* Payment confirmation
* Multi-location support

---

## Repository Contents

* workflow.json
* Workflow screenshots
* Documentation

---

Feel free to fork this project or use it as a starting point for your own AI business automation workflows.

