# Luma

Create images and video clips with Luma's generative models without leaving the conversation. Describe a shot and Luma generates it; ask for a change and Luma edits the result, extends a clip, restyles it, or reframes it to a new aspect ratio. Everything you make lands in a Luma workspace, so a follow-up can build on an earlier output instead of starting over.

## What you can do

- Generate images from a description
- Generate video clips from a description or an image
- Edit, extend, restyle and reframe what you made
- Run Luma's mini apps, such as Background Swap and Camera Angles, on your own photos
- Check your credit usage and the models available to you

## Get started

1. Install the plugin.
2. Open the plugin's **Connectors** tab, add **Luma**, select **Connect**, and sign in with your Luma account. Installing the plugin does not connect it. On Team and Enterprise plans, an Owner adds the connector for the organization first.
3. When you sign in, choose which of your Luma teams the plugin works as. Generations use that team's credits.

Try:

- Generate a product shot of a ceramic mug on a marble counter in soft morning light.
- Make a 5-second cinematic clip of waves rolling onto a beach at sunset.
- How many credits have I used this billing period?

## Troubleshooting

- **Every Luma request fails, or Claude says Luma isn't connected:** the plugin is installed but the connector isn't. Open the plugin's **Connectors** tab and connect **Luma**. On Team and Enterprise plans, ask an Owner to add the Luma connector for the organization first.
- **Sign-in doesn't finish:** close the sign-in window and select **Connect** again. Sign in with the account you use at [lumalabs.ai](https://lumalabs.ai).
- **A generation is refused for credits:** the team you chose at sign-in is out of credits for this billing period. Ask Claude for your credit usage to check.
- **A video seems stuck:** video runs take a few minutes. Ask Claude to check on the run.
- **Anything else:** contact [Luma support](https://luma-ai.support.site/).

## What this plugin runs and sends

This plugin contains no code. It points Claude at one remote MCP server, `https://agents.lumalabs.ai/mcp`, run by Luma AI.

- **Sign-in:** OAuth 2.1 with your Luma account. Claude never sees your Luma password.
- **What Luma receives:** the prompts and settings Claude sends to Luma's tools, any image or video you upload or point a tool at by URL, and the team you chose at sign-in.
- **What Luma returns:** generated images and video, links to them, run status, and your team's credit usage.
- **Where results are kept:** in the connected team's Luma workspace.

Luma's [privacy policy](https://lumalabs.ai/legal/privacy-policy) and [terms of service](https://lumalabs.ai/legal/terms-of-service) apply. Support: [luma-ai.support.site](https://luma-ai.support.site/).
