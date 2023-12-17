# The Cards theme for Micro.blog

Cards is a simple and lightweight theme for Micro.blog.

- Posts are styled as "Cards,” hence the theme name.
- Optimized for performance, accessibility, and SEO.
- Compatible with other plugins.
- Easily change the theme colors from your plugin settings.
- A toggle to allow visitors to toggle between light and dark mode.
- An option to enable Reading Time on posts greater than 1 minute long.
- An option to truncate posts on the home and category pages.
- An option to show Tinylytics Kudos below your
- Shows the post categories as links on the post page.

!["Card Theme Samples"](https://raw.githubusercontent.com/ericgregorich/micro-blog-cards-theme/master/screenshot.png)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M0DLOZR)

## Support

Email me from this [form](https://ericgregorich.com/email/) if you have any issues.

## Change Log
- 2023-12-17 v1.4.2 Tweaked the head tag to move the site title to the end (if there is a title). Very minor CSS tweak for tags.
- 2023-11-12 v1.4.1 Added pagination parameters that should enable/disable per page type based on your selection.
- 2023-11-12 v1.4.0 Added ability to sort category tags alphabetically. Thanks [@lostinhaste](https://micro.blog/lostinhaste)!
- 2023-11-06 v1.3.8 Renamed "Tags" to "Categories". Categories now show on all pages when Show Categories is enabled.
- 2023-09-10 v1.3.7 Minor CSS tweaks to nav and form controls.
- 2023-09-10 v1.3.6 Added setting to set the number of posts per page (pagination).
- 2023-09-10 v1.3.5 Updated to support Hugo 0.117. Tweaked the card shadows.
- 2023-08-14 v1.3.1 Minor bug fixes with code blocks.
- 2023-08-13 v1.3.0 Option to add tags to home page. Fixed stying issues.
- 2023-08-13 v1.2.2 Tweaked the default stying for code blocks.
- 2023-07-02 v1.2.1 Added support for Tinylytics Kudos.
- 2023-01-07 v1.1.9 Added setting to hide categories on the post.
- 2023-01-02 v1.1.8 Updated the style of categories on the post pages.
- 2023-01-01 v1.1.7 Fixed an issue where all posts were showing on category lists.
- 2023-01-01 v1.1.6 Now showing the category on post pages. Added option to truncate long post on home and list pages.
- 2022-12-16 v1.1.5 Added support to show Read Later time for posts greater than 1 minute.
- 2022-12-11 v1.1.4 Built in support for @Sod's Conversation and Reply by Email plugins. Just install and configure the plugin and it will automatically appear below your posts!
- 2022-12-09 v1.1.3 Fixed missing pagination. Added category title to category page. CSS fixes.
- 2022-12-09 v1.1.1 Added a Dark Theme toggle. Configure your light (default) and dark theme colors in settings.
- 2022-12-06 v1.1.0 Minor CSS fixes. Rounded logo. Tag updates.
- 2022-12-04 v1.0.9: Minor CSS fixes for tags on archive page. Now responsive.
- 2022-12-03 v1.0.8: Minor CSS fixes. Removed custom 404 page since it can be added as a page through the UI.

## Installation

- Open the Design page in your Micro.blog settings.
- Set your current theme to Blank and Hugo Version to 0.91 in the design section of your blog admin.
- Uninstall any theme that you already have installed.
- Install the Cards theme.

## Customizations

You can customize the colors in the Cards theme from your Plugin Settings screen.

The name of each setting should be self-explanatory. The Body colors affect the content outside the “cards,” and the Card colors affect the “cards” themselves.

> The colors may be overwritten when a new update to the theme is published. To avoid this, you can copy the content in the config.json file, update the theme, then paste the values back into the config.json file.

- Click on Design, then Custom Themes.
- Click on the config.json file in the Templates for Cards section.
- Copy the content, then go back.
- Update the Cards theme.
- Click on Design, then Custom Themes.
- Click on the config.json file in the Templates for Cards section.
- Paste the contents you copied earlier.
- Click on the Update Template button to save your changes.

## How to add additional customizations

The easiest (and safest) way to customize this theme is to create a new blank theme while the Cards theme is installed. You can customize the template files in your blank theme without changing this Cards theme.

When updates are pushed out to the Cards theme, the theme files will be updated automatically. Any custom theme files you have in your custom theme will be untouched.

## Tinylytics Kudos
[Tinylytics](https://tinylytics.app) is a lightweight, privacy focused analytics service created by @vincent. If you use Tinylyics on your Micro.blog site then you can easily enable the Kudos functionalty using the following steps.
1. Setup a Tinylytics account.
2. To configure Tinylytics on your Micro.blog site, I recommend the [Tinylytics for Micro.blog](https://micro.blog/account/plugins/view/101) plugin by @jimmitchell. It has everything you need to add Tinytics to your site. 
3. Open your Cards theme configuraiton and check the box labeled `Enable Tinylytics Kudos?`.
4. Your Kudos should then appear below your post.

