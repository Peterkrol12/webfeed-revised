# Changelog

## [0.9.0](https://pub.dev/packages/webfeed_revised/versions/0.9.0)
- Upgrade intl: ^0.20.0

## [0.8.0](https://pub.dev/packages/webfeed_revised/versions/0.8.0)
- Upgrade to Dart 3.0
- Upgrade xml: ^6.5.0
- Upgrade intl: ^0.19.0 - [Thanks to @bugrevealingbme](https://github.com/Peterkrol12/webfeed-revised/pull/10)
- Force RFC822 datetime to be parsed with `en_US` locale - [Thanks to @bbo76](https://github.com/Peterkrol12/webfeed-revised/pull/9)

## [0.7.3-beta](https://pub.dev/packages/webfeed_revised/versions/0.7.3-beta.1)
- Fixed html parser function
- Adds the ability to automatically parse and replace HTML tags from some elements of the RSS feed

## [0.7.2](https://pub.dev/packages/webfeed_revised/versions/0.7.2)
- Applied dart format

## [0.7.1](https://pub.dev/packages/webfeed_revised/versions/0.7.1)
- Updated dependencies
- Fixed RssItem pubDate optional seconds
- Added RssItem pubDate UTC parser
- Added RssItem description HTML parser
- Added documentation for public members

## [0.7.0](https://pub.dartlang.org/packages/webfeed/versions/0.7.0)
- Null safety migration [#50](https://github.com/witochandra/webfeed/pull/50)
- Parse duration if not empty [#39](https://github.com/witochandra/webfeed/pull/39)

## [0.6.0](https://pub.dartlang.org/packages/webfeed/versions/0.6.0)
- Refactor util/xml.dart
- Support RDF feed
- Support Syndication namespace

## [0.5.2](https://pub.dartlang.org/packages/webfeed/versions/0.5.2)
- Lower the xml package version constraints

## [0.5.1](https://pub.dartlang.org/packages/webfeed/versions/0.5.1)
- Support iTunes namespace [#19](https://github.com/witochandra/webfeed/pull/19)
- Parse date strings into DateTime [#22](https://github.com/witochandra/webfeed/pull/22)
- Add created & modified into dublin core namespace [#27](https://github.com/witochandra/webfeed/pull/27)
- Upgrade xml package [#28](https://github.com/witochandra/webfeed/issues/28) 
- Fix linting warnings

## [0.4.2](https://pub.dartlang.org/packages/webfeed/versions/0.4.2)
### Fixed
- Bad import in `rss_content.dart` & `rss_source.dart`

## [0.4.1](https://pub.dartlang.org/packages/webfeed/versions/0.4.1)
### Added
- Support `author` in RssFeed

## [0.4.0](https://pub.dartlang.org/packages/webfeed/versions/0.4.0)
### Added
- Support for dublin core namespace
- Support enclosure in rss item
- Set minimum dart version into 2

## [0.3.0](https://pub.dartlang.org/packages/webfeed/versions/0.3.0)
### Added
- Support for image namespace
