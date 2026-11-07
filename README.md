# n8n AI Prospecting Assistant

An AI-powered Telegram assistant built with n8n to help freelancers find potential clients, research businesses, and manage outreach.

## Demo

[Watch the project demo](https://youtube.com/shorts/S9Vl1jGersU?feature=share)

## Features

- **Lead Discovery:** Find potential clients using Google Places.
- **Business Research:** Research websites and collect publicly available contact information.
- **Contact Extraction:** Find business emails and social links.
- **AI Outreach:** Draft personalized outreach emails.
- **Human Approval:** Review and approve emails before they are sent.
- **Lead Management:** Save leads and track their status in Google Sheets.
- **Follow-ups:** Receive automated follow-up reminders.
- **Call Preparation:** Generate research notes before discovery calls.
- **Error Notifications:** Receive alerts when configured workflows encounter errors.

## How It Works

Telegram acts as the interface, while n8n runs the automation workflows. Google Sheets stores lead information, and AI services help with research and outreach.

## Included Workflows

1. Main Bot
2. Save Lead
3. Scrape Contact
4. Send Email Approval
5. Update Lead Status
6. Save Profile
7. Follow-up Reminders
8. Discovery Call Prep
9. Error Notifier

## Who Is This For?

Primarily freelancers who want to simplify finding and managing potential clients. It can also be adapted by consultants, small agencies, and independent professionals handling their own outreach. It works best for finding local businesses.

## Requirements

- n8n (cloud or self-hosted)
- Telegram Bot
- OpenAI API
- Google Places API
- Google Sheets and Gmail
- ScrapingBee
- Jina AI Reader

You will need your own accounts and API credentials. Some services may have usage costs.

## Setup

1. Download or clone this repository.
2. Import the nine workflow JSON files into n8n.
3. Follow the **AI Workflow Setup Guide** to configure credentials and connect the workflows.
4. Test the workflows before activating them.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
