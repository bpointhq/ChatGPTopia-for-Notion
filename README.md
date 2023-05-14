# ChatGPTopia for Notion 🤖💬

"ChatGPTopia for Notion" is a plugin developed to support efficient communication and seamless collaboration on the Notion platform. Utilizing GPT models with chatbot capabilities, this innovative plugin enables users to enhance their productivity and work efficiency on the information-sharing and collaborative Notion platform.

## Key Features ✨

- 🤖 Chatbot function powered by GPT models
- 💬 Efficient communication and seamless collaboration on Notion
- 🚀 Enhance productivity and work efficiency on Notion platform
- 💡 Innovative and effective approach to utilizing Notion

## Getting Started 🚀
To get started with ChatGPTopia for Notion, simply install the plugin on your Notion account and start using the chatbot feature. This plugin is compatible with various operating systems and devices.

## Contribution 🙌
Contribution to ChatGPTopia for Notion is always welcomed. Feel free to submit issues or pull requests on GitHub.

## License 📄
This plugin is licensed under the [MIT License](https://opensource.org/licenses/MIT).

# ChatGPT to Notion

[ChatGPT to Notion](https://chrome.google.com/webstore/detail/chatgpt-to-notion/oojndninaelbpllebamcojkdecjjhcle) brings the cleverness of ChatGPT into your favorite app!

## Overview

For information about the extension itself more than the code behind it, check out [this notion page](https://theo-lartigau.notion.site/theo-lartigau/ChatGPT-to-Notion-af29d9538dca4493a15bb4ed0fde7f91) or the [FAQ](https://github.com/L-a-r-t/chatgpt-to-notion/wiki/FAQ). This extension was built using the [Plasmo framework](https://www.plasmo.com/) and Typescript. A simple Express server (hosted on a free Render webservice) that can be found on the "server" branch, it allows the secure long-term storage of Notion's access tokens.

## Motive

While some tools already exist to save a webpage to Notion, and some going as far as allowing the user to save the page's contents, these solutions fall short when trying to save a conversation with ChatGPT. As such, providing a specialized extension to do this work efficiently felt natural.

## Usage

On ChatGPT's page, you'll notice a new pin icon under each of its answers. You can use it to save specifically that answer and the related prompt to your Notion database of choice. If you want to save the whole discussion, you can do so from the extension popup.

You may link as many databases with the extension as you need to, and you can then choose which database to save your discussion at saving time. If a page with the same title already exists in the database, the newly saved content will be appended to the end of said page.

### Websites access

Please refer to the [FAQ](https://github.com/L-a-r-t/chatgpt-to-notion/wiki/FAQ) for more info about the websites the extensions needs to access.

## Contribution

As this is my first time building a project that is open to contributions I will need a little time to sort things out and learn the best practices for great collaboration on GitHub. I'm also busy with some entrance exams until July 1st. If you want to help (thanks!), please stay patient for a few days.

## Roadmap

These are the things that I plan to work on at some point. I hope to have the following (ranked by priority) done in the near future:

- [ ] Support ChatGPT websearch and plugins (might already be the case but I couldn't test it yet)
- [ ] Document the code properly for anyone who's interested
- [ ] Improved chat formatting on some edge cases
- [x] Choose between saving an individual response to a new page or appending it to an existing page
- [x] Possibility to autosave conversations
- [x] Customize the page title upon saving (will assess if this is truly possible/useful)
