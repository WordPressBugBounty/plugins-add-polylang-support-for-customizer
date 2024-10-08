=== Add Polylang support for Customizer ===
Contributors: richardevcom,pers
Tags: polylang,customizer,support,translate,wordpress
Donate link: paypal.me/ricardsmucelans
Requires at least: 4.7
Tested up to: 6.1.1
Requires PHP: 5.6
Stable tag: trunk
License: GPL-2.0+
License URI: http://www.gnu.org/licenses/gpl-2.0.txt

This plugin adds Polylang support for WordPress Customizer.

== Description ==
# Add Polylang support for Customizer

This plugin adds Polylang support for WordPress Customizer.

## Support

We provide direct support via our [Frontbee Discord server](https://discord.gg/ZptSdXMPrM)

## Features

* Language switcher in Customizer.
* Localized theme_mods and options for both default and custom made Customizer values.
* Enable/disable forcing "The language is set from content" setting in Language->Settings->URL modifications

## Prerequisite

1. Polylang must be installed and activated.
2. Languages must be set in **Admin > Languages**.
3. _If you have a static front page_:
	1. _Create a front page per each language._
	2. _Select the front page in **Admin > Settings > Reading** per language._
5. Expect customizer to use setting type = `theme_mod` (default) as in:

`$wp_customize->add_setting( 'setting_id', [ 'type' => 'theme_mod', ] );`

## Installation

This plugin can be installed directly into your plugins folder \"as-is\"

or if you go to **Admin panel > Plugins > Add new > Upload Plugin** and select the archive containing this plugin.

It\'s safe to activate the plugin at this point. Because the plugin just injects some functionality - there will be no plugin menus or settings to play with.

## License

This plugin is licensed under the GPL v2 or later.

> This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License, version 2, as published by the Free Software Foundation.

> This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

> You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

A copy of the license is included in the root of the plugin’s directory. The file is named `LICENSE`.

## Important Notes

### Licensing

This plugin is licensed under the GPL v2 or later; however, if you opt to use third-party code that is not compatible with v2, then you may need to switch to using code that is GPL v3 compatible.

# Credits

Original solution made by [@soderlind](https://github.com/soderlind) is available [here](https://github.com/soderlind/customizer-polylang). Share some love! This is WordPress plugin version of his solution.


== Installation ==
This plugin can be installed directly into your plugins folder \"as-is\"
or if you go to Admin panel > Plugins > Add new > Upload Plugin and select the archive containing this plugin.

== Screenshots ==
1. Polylang language dropdown in Customizer

== Changelog ==
= 1.0.1 =
* First release
= 1.0.2 =
* Fixed issues with option rewriting and polylang translatable strings.
= 1.1.2 =
* Fixed issues with pll_current_language() missing due to Polylang API being not included.
= 1.1.2 =
* Added settings page & Enable/disable forcing "The language is set from content" setting in Language->Settings->URL modifications
= 1.1.2 =
* Added quick settings link
= 1.1.2 =
* Fixed missing includes
= 1.2.0 =
* Fixed 404 page & removed prefered language dismissal. Thanks @penhtech
= 1.3.0 =
* If Polylang is not active, don't run the app and throw an error notice
= 1.3.1 =
* Changed way Polylang API is called
= 1.3.2 =
* fixed API.php location error for multisites.
= 1.3.3 =
* Changed how API.php is included.
= 1.3.4 =
* Added Polylang PRO dir check
= 1.3.5 =
* Added Polylang PRO dir check
= 1.3.6 =
* Added Polylang PRO dir check
= 1.3.7 =
* Fixed no language selection issue on customizer.
= 1.3.8 =
* Fixed no language selection issue on customizer.
= 1.4.0 =
* Fixed premature Polylang API initialization error while activating/deactivating Polylang.
= 1.4.1 =
* Fixed non existing function (early) call for some 3rd party plugins.
= 1.4.2 =
* Added support up to WordPress 5.8
= 1.4.3 =
* Workaround for update version mismatch
= 1.4.5 =
* Added support URL
= 1.4.5 =
* Compatibility test