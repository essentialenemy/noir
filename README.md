Noir is a modern, responsive and customizable theme for Jekyll 4. Typography is paid close attention to and a dark mode friendly color scheme will be displayed automatically. It builds upon a standard Jekyll install in a number of ways.

### Demo

You can see a live demo of Noir: [https://noir.essentialenemy.com](https://noir.essentialenemy.com)

### Features

HTML, SASS and Config files are included for the theme's design and functionality.

A navigation area for linking to pages/posts or external URLs such as social media accounts.

404, Archive, Category, Tag, Style and About pages.

Pagination, related posts and per-post navigation to older/newer entries.

HTML/CSS compression (minification).

A favicon and valid Atom syndicated feed.

Variables based accent color for the theme which can be changed easily.

Fully responsive, with an emphasis on mobile friendly design and interaction.

Enabled forced curly/smart quotes across all content with the `{ | smartify }` liquid filter.

Rich preview links when shared via iMessage on iOS/macOS/watchOS.

A wide variety of HTML elements commonly used in online Markdown writing (blockquotes, headers, tables, boxes/buttons, figure captions, code blocks, footnotes) have been styled.

A single line added to a post's front matter can enable:
- Adding a category or tags to a post.
- The creation of *linked-list* style posts which link to external URLs, maintain a permalink and display a styled arrow to help indicate this.
- Additional date line listing the last date a post was modified on.

### Installation

First you will need to setup your Ruby environment and add the Jekyll and Bundler gems to it.

Detailed instructions for getting Ruby setup can be found [here](https://www.ruby-lang.org/en/documentation/installation/) and the installation guide for Jekyll can be found [here](https://jekyllrb.com/docs/installation/). Bundler makes managing Jekyll sites a lot easier and you can learn how to install that gem [here](https://bundler.io) (this theme’s installation guide uses Bundler).

Once that’s done it’s time for the fun part. Don’t even bother with the `jekyll new site` command, I am going to provide a more foolproof way so that you don’t wind up in dependencies hell.

1. Download the latest [release](https://github.com/essentialenemy/noir/releases/) (**NOT** the ZIP archive of the latest commit made, the latest **release** asset) of this repository and copy the files into a new directory where you want your site’s configuration files to live.
2. In your terminal or command prompt `cd` into the new directory you just made for those files.
3. Run the command: `bundle install` as this will install all of the dependencies I have named in `Gemfile.lock`.
4. Test that the site can be built with no issues, run the command: `bundle exec jekyll serve` and view the site by navigating to `127.0.0.1:4000` in your web browser.
5. If all is working fine you can begin customizing your site by making changes to `_config.yml`.

If you have any problems that arise I am glad to help you as much as I can. You can open a [new issue](https://github.com/essentialenemy/noir/issues), reach out to me on [Twitter](https://twitter.com/essentialenemy) or email me at the address found inside of `_config.yml`. I welcome your feedback and requests as well.

Thank you for your interest in Noir!
