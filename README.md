# N2K
Streamline site reviews, manage expectations, and keep your clients happy! Show clients what they need to see, and hide the rest.



## Concept
N2K (Need to Know) is a little Wordpress plugin built for developers and builders who would like to let clients browse their sites-in-progress at certain presentable breakpoints, and hide it at others.

As a developer, you will specify which breakpoints are currently "presentable" and which are not.  The plugin will compile custom media queries and inject them into the pages you specify.  If the device is within an "unpresentable" or “hidden” range, the user will be shown a friendly error message with a recommendation to use a viewport that is presentable.



## Installation
Install it just as you would any other Wordpress Plugin. Add the plugin folder to your plugins directory.  



## Usage
- Install, activate; The plugin will add a settings page within WP Admin
- Specify the pages on which to control visibility
- Specify your site's breakpoints
- Specify which of those breakpoints should be visible or hidden
- Choose a friendly error message template, or write your own

This plugin is ideal for developers who use a local development environment and deploy to a staging server for client review.  Activate this plugin on the staging site, not the local environment.

**Of course, remember to DEACTIVATE the plugin before pushing to production.** This is a development workflow plugin only, intended for use on development and staging sites. It is not intended for production.



## License
_[TODO] Unsure how to license this plugin, actually.  Will need to do my homework on Wordpress licensing._  A copy of the license will be included in the root of the plugin’s directory as `LICENSE`.



## Support, Issues, Development
The plugin is provided as-is with no pretense of commercial support.  Feedback is welcome and encouraged.  Issues, suggestions, and development [are managed through Github.](https://github.com/ensminger/n2k/issues)



## Credits
This project, like many others before it, is built on the grand master of Wordpress plugin frameworks, [Wordpress Plugin Boilerplate](http://wppb.io/), and includes the phenomenal product you all know as [ACF by Elliot Condon](https://www.advancedcustomfields.com/).

All additional code, comments, and opinions expressed in this plugin are either my own, or the contributions of the esteemed Github community.

-- Phil Ensminger | [ensm.in/ger](http://ensm.in/ger)

--------------

> NOTE: This plugin does not yet exist.  This README is the first test of its viability and potential usefulness.  Would you use a plugin like this?  Do you identify with the problem that it solves? How could it be better?  Tell me: phil@ensminger.io
