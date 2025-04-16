# ExpertAI Chatbot

**A domain-aware AI chatbot that intelligently filters responses based on your website’s keywords and context. Instead of answering everything, it focuses on content relevant to your site.**

## Description

ExpertAI Chatbot transforms your website into a domain-specific AI assistant. Instead of providing generic answers, it uses your site’s keywords and content to determine what’s relevant—so your visitors get focused, intelligent help.

This chatbot is ideal for websites where specificity matters. Whether you're offering investment guidance, biotech research information, education tools, or technical support, ExpertAI ensures that responses align with your site's intent and audience.

### How It Works

- Admins generate keywords using content from posts, pages, custom post types, and ACF fields. These are automatically suggested but can be edited manually.
- When a user asks a question, the chatbot checks for keyword relevance—both literal and semantic—before querying the OpenAI API.
- Irrelevant questions receive a customizable fallback message instead of a generic AI response.
- All conversations happen in a familiar chat-style interface, maintaining a clear, focused experience.

ExpertAI supports internationalization and accessibility for broad compatibility and ease of use.

## Installation

1. Upload the plugin folder to `/wp-content/plugins/` or install via the WordPress Plugins screen.
2. Activate the plugin.
3. Go to **ExpertAI Chatbot** in the admin dashboard to configure:
   - OpenAI API Key
   - Model selection (e.g., GPT-4)
   - Keyword generation and editing
   - Custom branding and fallback messaging

The chatbot will automatically appear on the frontend of every page after activation.

## Frequently Asked Questions

### Can I control what questions the chatbot responds to?

Yes. ExpertAI checks your question against saved keywords and site content before generating a response. Irrelevant questions receive a fallback message instead.

### What’s the fallback message?

If a question isn’t related to your site’s keywords or context, ExpertAI will show a polite fallback such as:

> “That’s not currently part of my knowledge domain. Please try rephrasing your question.”

This message is fully customizable.

### Can I customize the chatbot’s appearance?

Yes. You can upload a custom icon and adjust branding styles including background and text color.

### Does it work on all WordPress sites?

Yes. ExpertAI is a standalone plugin and works with any modern WordPress theme.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for release notes.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) if you’d like to help improve this plugin.

## License

This plugin is licensed under the [GNU General Public License v2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html).
