Domain Switcher Bookmarklets
============================

A couple of handy Firefox bookmarklets for jumping between development and production domains, without affecting the path of the page you're current on.

The first bookmarklet lets you jump between a local testing domain (e.g. `example.l`) and and the live site (e.g. `example.com`), and vice versa:

![Jumping from .l to .com and vice versa](https://github.com/paulherron/domain_switcher/raw/master/images/tld_switch.gif)

The second one simply removes the 'subdomain' portion of a <abbr title="Uniform Resource Locator">URL</abbr>, which is handy for jumping from a dev site (e.g. `dev.example.com`) to the production site (e.g. `example.com`):

![Jumping from the dev domain to the production domain](https://github.com/paulherron/domain_switcher/raw/master/images/remove_subdomain.gif)


Using as keyword bookmarks
--------------------------

The above saves a little time but where they become more useful is if you assign them as keyword bookmarks, so you can fire them without having to reach for the mouse.

For example, I've assigned the first bookmarklet as `!`. So, to toggle domains I can type `Cmd-l` (to get to the address bar), then `!<Enter>` to make the jump. You can optionally specify a <abbr title="Top Level Domain">TLD</abbr> to switch to, for example: `! org`.

I've assigned the second bookmarklet the keyword of `-`.


Install
-------

Open up `index.html` and drag the bookmarklets to your bookmark bar. Optionally, right-click on the bookmark entry and enter a 'keyword' value so you can access the bookmark from the address bar.
