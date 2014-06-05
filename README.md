mediawiki-core-vendor-swiftmailer
=================================

Github mirror of "mediawiki/core/vendor/swiftmailer" - our actual code is hosted with Gerrit (please see https://www.mediawiki.org/wiki/Developer_access for contributing

[Composer] managed SwiftMailer librariy fork recommended for use with [MediaWiki].
This repository is maintained for use on the Wikimedia Foundation production
and testing clusters. MediaWiki uses the code under release-tag 5.2.0-patch

Swift Mailer
------------

Swift Mailer is a component based mailing solution for PHP 5.
It is released under the MIT license.

Homepage:      http://swiftmailer.org
Mediawiki Release:- https://github.com/wikimedia/mediawiki-core-vendor-swiftmailer/tree/5.2.0-patch
Swift Mailer is highly object-oriented by design and lends itself
to use in complex web application with a great deal of flexibility.

Usage
-----
Checkout this library into $IP/vendor/swiftmailer/ using `git clone <URL>`.

1. Add the following to your 'composer.json' file
  ```javascript
	"repositories": [
		{
			"type": "vcs",
			"url": "https://github.com/wikimedia/mediawiki-core-vendor-swiftmailer"
		}
	],
	"require": {
		"php": ">=5.3.2",
		"swiftmailer/swiftmailer": "5.2.0-patch"
	},
   ```
2. Run `composer update --optimize-autoloader` to download files and update
   the autoloader files.
   
[Composer]: https://getcomposer.org/
[MediaWiki]: https://www.mediawiki.org/wiki/MediaWiki
