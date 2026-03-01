# action-repo

Dummy repository used to trigger GitHub webhook events (**Push**, **Pull Request**, **Merge**).

These events are captured by the [webhook-repo](../webhook-repo/) endpoint and stored in MongoDB for display in the UI.

## Usage

1. Push commits, open pull requests, or merge branches in this repo.
2. GitHub sends the corresponding webhook payload to the registered endpoint.
3. The webhook receiver parses and stores the event, which then appears in the dashboard.
4. This point is used in test -> PUSH.
5. This point is used in test -> PULL
