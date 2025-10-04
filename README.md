# n8n RSS Feed Notifier

This n8n workflow fetches the latest post from Ethan Mollick's "One Useful Thing" RSS feed and sends the title and link to a specified endpoint.

## How It Works

The workflow is triggered whenever a new item is published to the RSS feed. It then extracts the post's title and URL and sends them via an HTTP POST request to a pre-configured webhook.

**Nodes Used:**
*   **RSS Feed Read**: The trigger that monitors `https://www.oneusefulthing.org/feed`.
*   **HTTP Request**: The action that sends the data to a destination.

## Setup

1.  Download the `n8n.json` file from this repository.
2.  Import the workflow into your n8n instance.
3.  Open the "Send to Webhook" (HTTP Request) node.
4.  Replace the placeholder URL (`https://example.com/webhook_placeholder`) with your actual webhook URL.
5.  Activate the workflow.
