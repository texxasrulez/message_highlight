message_highlight
=================

![Downloads](https://img.shields.io/github/downloads/texxasrulez/message_highlight/total?style=plastic&logo=github&logoColor=white&label=Downloads&labelColor=aqua&color=blue)
[![Packagist Downloads](https://img.shields.io/packagist/dt/texxasrulez/message_highlight?style=plastic&logo=packagist&logoColor=white&label=Downloads&labelColor=blue&color=gold)](https://packagist.org/packages/texxasrulez/message_highlight)
[![Packagist Version](https://img.shields.io/packagist/v/texxasrulez/message_highlight?style=plastic&logo=packagist&logoColor=white&label=Version&labelColor=blue&color=limegreen)](https://packagist.org/packages/texxasrulez/message_highlight)
[![Github License](https://img.shields.io/github/license/texxasrulez/message_highlight?style=plastic&logo=github&label=License&labelColor=blue&color=coral)](https://github.com/texxasrulez/message_highlight/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/texxasrulez/message_highlight?style=plastic&logo=github&label=Stars&labelColor=blue&color=deepskyblue)](https://github.com/texxasrulez/message_highlight/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/texxasrulez/message_highlight?style=plastic&logo=github&label=Issues&labelColor=blue&color=aqua)](https://github.com/texxasrulez/message_highlight/issues)
[![GitHub Contributors](https://img.shields.io/github/contributors/texxasrulez/message_highlight?style=plastic&logo=github&logoColor=white&label=Contributors&labelColor=blue&color=orchid)](https://github.com/texxasrulez/message_highlight/graphs/contributors)
[![GitHub Forks](https://img.shields.io/github/forks/texxasrulez/message_highlight?style=plastic&logo=github&logoColor=white&label=Forks&labelColor=blue&color=darkorange)](https://github.com/texxasrulez/message_highlight/forks)
[![Donate Paypal](https://img.shields.io/badge/Paypal-Money_Please!-blue.svg?style=plastic&labelColor=blue&color=forestgreen&logo=paypal)](https://www.paypal.me/texxasrulez)

With this plugin you can colorize the message index rows based on specific criteria like sender, recipient and subject.

FEATURES
--------

Go to roundcube settings area and select rules to highlight emails in your mailview.

CONTACT
-------
Author:   Cor Bosman (cor@roundcu.be)

Bug reports through github (https://github.com/corbosman/message_highlight/issues)

LICENSE
-------

This plugin is distributed under the GNU General Public License Version 2.
Please read through the file LICENSE for more information about this license.

## Versioning
- `message_highlight` now keeps its canonical version in `message_highlight::PLUGIN_VERSION` inside `message_highlight.php`.
- `message_highlight::info()` exposes the plugin metadata array used for self-identification.
- Development builds should use a `+dev` suffix such as `1.0.2+dev`.
- Release builds should use a clean tagged version such as `1.0.2`.

For a release bump:
1. Update `message_highlight::PLUGIN_VERSION` in `message_highlight.php` or run `sh scripts/bump-version.sh 1.0.2`.
2. Update `CHANGELOG.md`.
3. Create the matching release tag after verification.

