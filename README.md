phpcs-magento-rules
===================

PHPCS rules for working with Magento

These code sniffer rules were created from the standards listed at the location below:

[Magento 2 PHP Coding Standards](https://wiki.magento.com/display/MAGE2DOC/PHP+Coding+Standards+Tests#PHPCodingStandardsTests-PHPCodeSnifferExclusions)

The `ruleset.xml` file should be placed in a "Mage" folder under your PHPCS Standards folder. I was able to find the location of the coding standards by running the following command:

```
cd $(dirname `which phpcs`)/../lib/php/PHP/CodeSniffer/Standards
```

If that does not work, you could find the location by calling:

```
cd $(dirname `which phpcs`)/../share/php/PHP/CodeSniffer/Standards
```
