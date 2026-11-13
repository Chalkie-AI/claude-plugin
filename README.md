# Chalkie for Claude

Chalkie creates teaching resources with AI. This plugin lets Claude create slide lessons, quizzes and printable worksheets in your Chalkie account, plan connected lesson series, find and preview resources you already made, and recreate a resource from its saved settings.

## What's inside

- **Chalkie connector** (`https://api.chalkie.ai/mcp`): create, search, read, preview and recreate resources in your account.
- **creation skill**: how Claude gathers a short teaching brief, picks valid settings, plans connected lessons and recurring characters, and follows generation to completion.
- **recreation skill**: how Claude recreates a lesson or worksheet from its saved settings without changing the original.

## Get started

1. Install the plugin.
2. Open the plugin's **Connectors** tab, connect Chalkie and sign in with your Chalkie account.
3. Ask Claude for something like "Make a Year 5 lesson on equivalent fractions."

On Team and Enterprise plans, an Owner adds the connector for the organisation first.

## Data

The plugin runs no scripts or hooks. It only talks to `https://api.chalkie.ai/mcp`, signed in as you through Chalkie's OAuth.

- **Sent to Chalkie:** what you ask Claude to create or find, such as topics, class year, instructions and resource IDs.
- **Stored by Chalkie:** the lessons, quizzes and worksheets you create, saved in your Chalkie account like anything made in the app.
- **Nowhere else:** the plugin sends nothing to any other service. Chalkie uses AI providers to generate content, as its [privacy policy](https://chalkie.ai/privacy) describes.

Chalkie is for teachers. Don't use it to share students' personal information.

## Need help?

- Website: https://chalkie.ai
- Support: support@chalkie.ai
- Privacy policy: https://chalkie.ai/privacy
- Terms: https://chalkie.ai/terms
