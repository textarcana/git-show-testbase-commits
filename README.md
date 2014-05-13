git-show-testbase-commits
=======================

Show recent commits on files whose names include the string "test."

## Usage

    ./git_show_testbase_commits <path> <days ago>

For example:

    ./git_show_testbase_commits ~/my-repo 10
    ./git_show_testbase_commits . 28


## Example output

    $ ./git_show_testbase_commits ~/mediawiki-core 10

    72c0ce4 (7 days ago) Ori Livneh: tests/parser/parserTest.inc
    9d69b15 (8 days ago) addshore: tests/phpunit/MediaWikiPHPUnitCommand.php
    9d69b15 (8 days ago) addshore: tests/phpunit/bootstrap.php
    71fc32c (2 weeks ago) Bryan Davis: tests/phpunit/data/gitinfo/info-testValidJsonData.json
    71fc32c (2 weeks ago) Bryan Davis: tests/phpunit/includes/GitInfoTest.php
    f14e48f (8 days ago) Jackmcbarn: tests/phpunit/includes/MWNamespaceTest.php
    48d5e5b (1 year, 7 months ago) daniel: tests/phpunit/includes/content/ContentHandlerTest.php
    48d5e5b (1 year, 7 months ago) daniel: tests/phpunit/includes/content/CssContentTest.php
    48d5e5b (1 year, 7 months ago) daniel: tests/phpunit/includes/content/TextContentTest.php
    72c0ce4 (7 days ago) Ori Livneh: tests/phpunit/includes/parser/NewParserTest.php
    5a81ad0 (7 months ago) Brian Wolff: tests/phpunit/includes/parser/ParserMethodsTest.php
    3ca5ecb (4 days ago) physikerwelt (Moritz Schubotz): tests/phpunit/install-phpunit.sh
    e7867c8 (8 days ago) addshore: tests/phpunit/phpunit.php
    fefc843 (8 days ago) addshore: tests/phpunit/suite.xml
    4ffb4cf (9 days ago) rillke: tests/qunit/QUnitTestResources.php
    4ffb4cf (9 days ago) rillke: tests/qunit/suites/resources/mediawiki.api/mediawiki.api.category.test.js
    93fc25c (13 days ago) jrobson: tests/qunit/suites/resources/mediawiki.api/mediawiki.api.test.js
    40b569a (5 days ago) Timo Tijhof: tests/qunit/suites/resources/mediawiki/mediawiki.user.test.jsU
