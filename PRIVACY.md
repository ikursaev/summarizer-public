# Privacy Policy

**YouTube AI Summarizer**
Last updated: December 20, 2024

## Overview

YouTube AI Summarizer is a browser extension that helps you summarize YouTube videos using AI. This privacy policy explains what data the extension accesses and how it is handled.

## Data Collection

### What We Collect

**We do not collect, store, or transmit any of your personal data to our servers.** The extension operates entirely on your device.

### Data Stored Locally

The following data is stored locally in your browser using Chrome's storage APIs:

| Data | Purpose | Storage Type |
|------|---------|--------------|
| API keys | Authenticate with AI providers (Gemini, OpenAI, Anthropic) | Local only (not synced) |
| Extension settings | Your preferences (theme, models, auto-summarize options) | Synced across devices |
| Summaries | Generated video summaries for quick access | Local only |
| Chat history | Conversation history for follow-up questions | Local only |

**You can clear all stored data at any time** by removing the extension or clearing extension data in your browser settings.

## Third-Party Services

The extension communicates with the following third-party AI services to generate summaries:

| Service | Data Sent | Privacy Policy |
|---------|-----------|----------------|
| Google Gemini API | Video URL, captions, or video content | [Google AI Privacy](https://ai.google.dev/terms) |
| OpenAI API | Video captions | [OpenAI Privacy](https://openai.com/privacy) |
| Anthropic API | Video captions | [Anthropic Privacy](https://www.anthropic.com/privacy) |

**Important**:
- Your API keys are sent directly to these services for authentication
- Video content (URLs, captions, or footage) is sent for summarization
- We do not proxy or store any of this data on our servers
- Each provider handles data according to their own privacy policy

## Permissions

The extension requires these browser permissions:

| Permission | Purpose |
|------------|---------|
| `storage` | Save your settings and summaries locally |
| `tabs` | Detect when you're on a YouTube page |
| `scripting` | Inject summarize buttons on YouTube pages |
| `host_permissions` (YouTube) | Access YouTube page content for caption extraction |
| `host_permissions` (AI APIs) | Send requests to AI providers |

## Data Sharing

**We do not sell, share, or transfer your data to any third parties** beyond the AI providers you explicitly configure and use.

## Children's Privacy

This extension is not directed at children under 13. We do not knowingly collect any information from children.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated" date above.

## Contact

If you have questions about this privacy policy, please open an issue on our [GitHub repository](https://github.com/ikursaev/summarizer/issues).

## Your Rights

You have full control over your data:
- **Access**: All data is stored locally in your browser
- **Delete**: Remove the extension or clear browser data
- **Portability**: Export your Chrome profile to transfer settings


