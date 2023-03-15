<img src="http://getkirby.com/assets/images/github/starterkit.jpg" width="300">


**Kirby: the CMS that adapts to any project, loved by developers and editors alike.**  
The Starterkit is a full-blown Kirby installation with a lot of example content, blueprints, templates and more.  
It is ideal for new users to explore many of Kirby's options and get to know the Panel.

You can learn more about Kirby at [getkirby.com](https://getkirby.com).

<img src="http://getkirby.com/assets/images/github/starterkit-screen.png" />

### Try Kirby for free  
You can try Kirby and the Starterkit on your local machine or on a test server as long as you need to make sure it is the right tool for your next project. … and when you’re convinced, [buy your license](https://getkirby.com/buy).

The starterkit is a demo of basic Kirby features. It's not recommended to be used "as is" in production. Please, follow our documentation closely for more features and guides on how to build secure, high-quality websites with Kirby.

### Get going
Read our guide on [how to get started with Kirby](https://getkirby.com/docs/guide/quickstart).

You can download the latest version of the Starterkit from https://download.getkirby.com/.  
If you are familiar with Git, you can clone Kirby's Starterkit repository from Github.

    git clone https://github.com/getkirby/starterkit.git

## What's Kirby?
- **[getkirby.com](https://getkirby.com)** – Get to know the CMS.
- **[Try it](https://getkirby.com/try)** – Take a test ride with our online demo. Or download one of our kits to get started.
- **[Documentation](https://getkirby.com/docs/guide)** – Read the official guide, reference and cookbook recipes.
- **[Issues](https://github.com/getkirby/kirby/issues)** – Report bugs and other problems.
- **[Feedback](https://feedback.getkirby.com)** – You have an idea for Kirby? Share it.
- **[Forum](https://forum.getkirby.com)** – Whenever you get stuck, don't hesitate to reach out for questions and support.
- **[Discord](https://chat.getkirby.com)** – Hang out and meet the community.
- **[YouTube](https://youtube.com/kirbyCasts)** - Watch the latest video tutorials visually with Bastian.
- **[Twitter](https://twitter.com/getkirby)** – Spread the word.
- **[Instagram](https://www.instagram.com/getkirby/)** – Share your creations: #madewithkirby.

## Local Development with Valet

To run valet run the [park](https://laravel.com/docs/8.x/valet#serving-sites) command:

    valet park

That's all there is to it. Now, any application you create within your "parked" directory will automatically be served using the http://<directory-name>.test.

## Local Development with Browsersync & Tailwind

[How to set up local development for Kirby and Tailwind — using the command line on macOS](https://www.brianliddell.com/blog/how-to-set-up-local-development-for-kirby-and-tailwind-version-2)

[Tailwinds Docs](https://tailwindcss.com/docs/utility-first)

After the above is complete to run browsersyc:

    browser-sync start --proxy "https://deegoo-tattoo.test" --files "assets/style.css, site/snippets/*.php, site/templates/*.php, content/**/*.txt"

Also, in a new terminal window run `npm run watch` to watch the changes on style.css.

---

© 2009-2022 Bastian Allgeier  
[getkirby.com](https://getkirby.com) · [License agreement](https://getkirby.com/license)

## Update Kirby (for the future)

- [Updating kirby](https://getkirby.com/docs/cookbook/setup/git#updating-kirby)
