<h1 align="center">Gmail AI Assistant</h1>

<p align="center">
An AI-powered email assistant that analyzes Gmail messages, extracts important information, and helps users respond faster through Telegram.
</p>


## Overview

Gmail AI Assistant uses Artificial Intelligence to transform incoming emails into structured insights.

Instead of manually reading long emails, users receive:

- AI-generated summaries
- Priority assessment
- Important information extraction
- Spam and promotional classification
- Suggested replies
- One-click AI-powered email responses


## Features

### User Registration

- Allow users to connect their Gmail account through Telegram.
- Link Telegram users with their Gmail accounts for personalized email assistance.
- Support multiple users with separate accounts.

### Multi-User Support

- Support multiple users using the same Gmail Assistant workflows.
- Maintain a separate Gmail account and Telegram account for each user.
- Store each user's Gmail OAuth refresh token securely for authentication.
- Refresh Gmail access tokens independently for each user.
- Process each user's emails independently.
- Send email analyses and reply confirmations to the correct Telegram user.
- Send replies through the correct user's Gmail account.


### Email Intelligence

- Automatically analyze incoming Gmail messages.
- Extract structured information from emails.
- Generate summaries, priority assessment, and suggested actions.
- Store analyzed emails and AI-generated replies for reliable follow-up actions.

### AI Email Analysis

- Generate concise email summaries.
- Extract key information from emails.
- Classify email priority:
  - High
  - Medium
  - Low
- Automatically categorize emails based on their content.
- Detect promotional emails and potential spam.

### Telegram Assistant

- Receive AI email analysis directly in Telegram.
- Review suggested replies.
- Send AI-generated replies to Gmail with one click.
- Receive confirmation after successful delivery.
- Reply to specific emails using message IDs.

## Technologies

- n8n
- Gmail API
- Telegram Bot API
- OpenRouter
- Large Language Models (LLMs)
- JavaScript


## Project Status

This project is currently under active development.

The goal is to build a complete AI email assistant capable of understanding emails, managing conversations, and reducing manual email workload.


## Future Improvements

- [x] Read the full email body instead of using the Gmail snippet.
- [x] Improve HTML parsing and email content cleaning.
- [x] Support one-click AI-generated replies directly from Telegram.
- [x] Store email and reply information for future processing.
- [x] Add user registration and link Telegram users with their Gmail accounts.
- [x] Reply to specific emails using message IDs instead of only thread IDs.
- [x] Add email categories (work, personal, promotions, newsletters, etc.).
- [x] Support multiple Gmail accounts.
- [ ] Add calendar event creation for meeting requests.
- [ ] Use advanced paid LLM APIs for improved quality and reliability.
- [ ] Add memory to maintain context from previous conversations.
- [ ] Detect already answered emails to prevent duplicate replies.
- [ ] Track reply history and conversation status.
- [ ] Allow users to edit AI-generated replies before sending.
- [ ] Generate multiple reply options with different tones.
- [ ] Add attachment analysis for PDFs, documents, and images.
- [ ] Extract tasks and action items from emails.
- [ ] Create automatic reminders for follow-up emails.
- [ ] Learn user writing style and preferences.
- [ ] Add multi-language email support.
- [ ] Improve phishing and security detection.
- [ ] Build a dashboard for email insights and analytics.


## Changelog

### v0.8.0 - Multi-User Handling

- Added multi-user support.
- Added independent Gmail authentication for each user.
- Added per-user Gmail access token handling.
- Added independent email processing for each registered user.
- Added user-specific Telegram notifications.
- Added user-specific Gmail reply handling.

#### v0.7.1 - Reply Status Tracking

- Fixed email status tracking after successful replies.
- Updated the analyzed email status from pending to replied after sending a reply.

### v0.7.0 - Email Categorization

- Added AI-powered email categorization.
- Added category information to email analysis and storage.

### v0.6.1 - Email Reply Content Cleaning

- Improved email cleaning for replied messages.

### v0.6.0 - Message-Specific Replies

- Added support for replying to specific emails using message IDs.
- Improved reply accuracy by targeting the original email message.

### v0.5.0 - User Registration & Account Linking

- Added user registration through Telegram.
- Added Gmail account linking for Telegram users.
- Added support for personalized email notifications per user.

### v0.4.0 - Telegram Reply Assistant

- Added one-click AI-generated email replies through Telegram.
- Added reply tracking using stored email information.
- Added confirmation messages after successful replies.

### v0.3.0 - Email Content Intelligence

- Added full email body extraction.
- Added HTML cleaning to remove unnecessary content.
- Improved AI analysis quality with cleaner inputs.

### v0.2.0 - AI Email Analysis

- Added structured AI email analysis.
- Added summary generation, priority detection, and spam assessment.

### v0.1.0 - Initial Release

- Added Gmail integration.
- Added Telegram notifications.
- Added AI-powered email analysis.


## License

All rights reserved.
