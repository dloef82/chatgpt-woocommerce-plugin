# WooCommerce ChatGPT Plugin

This is a ChatGPT plugin that connects to your WooCommerce store, allowing the AI to compile carts based on user input.

## Features

- Add a product to the cart using ChatGPT

## Setup

1. Clone this repository or download the files.
2. Follow the instructions in the [ChatGPT plugin guide](https://example.com/chatgpt-plugin-guide) to set up your WooCommerce store API and configure the plugin.
3. Update the `ai-plugin.json` file with the necessary details, such as authentication URLs, client ID, and client secret.
4. Host the `ai-plugin.json` and `woocommerce-chatgpt-plugin.yaml` files on your server, making sure they are accessible via the specified URLs in the manifest file.
5. Implement the server-side logic to handle OAuth2 authentication and the required API endpoints.

## Usage

Once the plugin is set up, ChatGPT will be able to interact with your WooCommerce store through the specified API endpoints. For example, you can use the following command to add a product to the cart:

Add product with ID 123 to the cart with a quantity of 2.

