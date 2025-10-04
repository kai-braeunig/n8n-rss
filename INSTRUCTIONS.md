# Setup Instructions

## Run the Workflow

1.  **Start n8n**: In a GitHub Codespaces terminal, run the command `npx n8n`. Wait for the `http://localhost:5678` URL to appear.
2.  **Open n8n**: `Ctrl+Click` the URL to open the n8n web interface.
3.  **Import Workflow**:
    *   Copy the raw JSON content from the `n8n.json` file in this repository.
    *   In the n8n UI, press `Ctrl+I` (or `Cmd+I`) and paste the JSON to import the workflow.
4.  **Test**: Click the "Test workflow" button in the n8n UI.

## Verify the Output

1.  **Subscribe**: Open a new browser tab to `https://ntfy.sh/my-n8n-test-feed-ax78` (or your unique topic URL).
2.  **Check**: After testing the workflow, a notification with the latest post from Ethan Mollick's blog should appear on this page.
