# Discord IP Info Webhook

This JavaScript code enables you to retrieve IP information and send it to a Discord webhook. It collects details about the visitor's IP address, location, and VPN usage and sends an embed message to a Discord channel. It can be useful for tracking website visitors or monitoring IP activity.

## Getting Started

To use this code, follow these steps:

1. Add the following script tag to your HTML file, preferably just before the closing `</body>` tag:

   ```html
   <script src="javascript/webhook.js"></script>

2. Obtain a token from ipinfo.io. You can get a token by signing up for a free account on their website.

3. Replace `<your-token>` in the following URL with your actual token: https://ipinfo.io/json?token=<your-token>.

4. Open the webhook.js file and locate the ipInfoUrl and vpnInfoUrl variables. Replace the token parameter in both URLs with your token.

5. Ensure that the webhook.js file is located in a javascript folder within your project directory. Adjust the src attribute of the script tag in your HTML file accordingly.

6. By replacing the `<your-webhook-url>` placeholder with your actual Discord webhook URL, the IP information will be sent to the specified Discord channel when a visitor accesses your web page. Make sure to test it to ensure that the webhook is functioning as expected.

7. Now When the visitor accesses your web page, their IP information will be sent to the Discord webhook.

