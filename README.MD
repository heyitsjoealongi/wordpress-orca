![WordPress Orca Banner](https://raw.githubusercontent.com/heyitsjoealongi/wordpress-orca/main/images/wordpress-orca.png)

# WordPress Orca

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000) [![License: MIT ](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/heyitsjoealongi/wordpress-orca/blob/master/LICENSE) [![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fheyitsjoealongi%2Fwordpress-orca.svg?type=small)](https://app.fossa.com/projects/git%2Bgithub.com%2Fheyitsjoealongi%2Fwordpress-orca?ref=badge_small)

WordPress Orca for building lightweight applications in PHP, JavaScript, and CSS (Template), this configuration available by [Open Source](https://opensource.org/).

## Contents

- [About](#about)
- [Build](#build)
- [Overview](#overview)
  - [Requirements](#requirements)
  - [Installation](#installation)
- [Additional](#additional)

## About

WordPress Orca is a lightweight PHP, JavaScript, and CSS theme template for WordPress.

![GitHub stars](https://img.shields.io/github/stars/heyitsjoealongi/wordpress-orca?style=social) ![Twitter Follow](https://img.shields.io/twitter/follow/heyitsjoealongi)

- Website: [heyitsjoealongi.com](https://heyitsjoealongi.com/)
- X: [@heyitsjoealongi](https://x.com/heyitsjoealongi/)
- GitHub: [@heyitsjoealongi](https://github.com/heyitsjoealongi/)
- LinkedIn: [@heyitsjoealongi](https://www.linkedin.com/in/heyitsjoealongi/)

## Build

WordPress Orca is built with the most minimal components and styling possible, shaped from the original, based on Underscores from [Automattic](https://automattic.com/), templated by ACF (Advanced Custom Fields).

- [WordPress](https://wordpress.com/)
- [Underscores](https://underscores.me/)
- [Advanced Custom Fields](https://www.advancedcustomfields.com/)

## Overview

### Requirements

This project runs on WordPress, using minimal PHP, JavaScript, and CSS all dynamically templated by ACF.

- WordPress (v6.5.3)
- ACF (v6.2.9)

### Installation

- Create a WordPress hosting configuration from [wordpress.com](https://wordpress.com/hosting/) or [wordpress.org](https://wordpress.org/)
- Compress this folder in a ZIP archive format
- Install the WordPress theme within the WordPress Admin panel by going to Appearance -> Themes, then clicking 'Install new theme', and then click [Upload Theme](https://wordpress.org/documentation/article/work-with-themes/), click choose file, then 'Install Now', after the theme has installed, click 'Activate'
- Create, a Home, Articles, About, and Privacy Policy within the WordPress Admin panel by going to Pages -> All Pages
- Install the Advanced Custom Fields plugin within the WordPress Admin panel by going to Plugins -> Add New Plugin and searching for [Advanced Custom Fields](https://wordpress.com/plugins/advanced-custom-fields) then click 'Install and activate'
- Import the custom fields within the WordPress Admin panel by going to ACF -> Tools, then clicking 'Choose file', and then 'Import json'
- Make sure that the page templates correspond with the pages
  - All Articles (Page Templates -> Is Equal To -> Articles Page)
  - Experience (Page Templates -> Is Equal To -> About Page)
  - Featured Articles (Page Templates -> Is Equal To -> Home Page)
  - Introduction (Page Templates -> Is Equal To -> About Page Or Page Templates -> Is Equal To -> Articles Page)
  - Introduction Extra (Page Templates -> Is Equal To -> Home Page)

## Additional

##### Bugs and Issues

Having an issue with the template? Report bugs & issues with WordPress Orca on GitHub via [Issues](https://github.com/heyitsjoealongi/wordpress-orca/issues). Fork, Pull, or Send an email over to join as a contributor! Join in on the open source conversation on [X](https://x.com/heyitsjoealongi).

##### Acknowledgments

- [Orca Logo](https://thenounproject.com/icon/orca-6567407/)

##### Additional Acknowledgments

##### License

© 2024 WordPress Orca released via [MIT](https://opensource.org/licenses/MIT) license. Information on this license can be viewed as it applies to this repository on GitHub at [WordPress Orca License](https://github.com/heyitsjoealongi/wordpress-orca/blob/main/LICENSE).

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fheyitsjoealongi%2Fwordpress-orca.svg?type=large&issueType=license)](https://app.fossa.com/projects/git%2Bgithub.com%2Fheyitsjoealongi%2Fwordpress-orca?ref=badge_large&issueType=license)
