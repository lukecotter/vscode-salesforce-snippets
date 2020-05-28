# Salesforce Snippets for Salesforce (Apex) Development

[![Version](https://vsmarketplacebadge.apphb.com/version-short/lcotter.salesforce-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/lcotter.salesforce-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/lcotter.salesforce-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets)

<p align="center">
  <br />
  <img src="https://raw.githubusercontent.com/lukecotter/vscode-salesforce/master/images/icon.png" alt="Salesforce Snippets Logo" width=25%"/>
</p>

Code snippets for Salesforce (Apex) for [Vs Code](https://code.visualstudio.com/) editor. Additional useful code snippets not included in the [Salesforce Extension Pack](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode) and improved syntax of some that are.

## Installation

1. Launch VS Code Quick Open `Ctrl`-`P` (Windows, Linux) or `Cmd`-`P` (OSX)
1. paste `ext install lcotter.salesforce-snippets` and press enter.

or

1. Search for [Salesforce Snippets](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets) in the extensions market place and install it.

## Supported languages (file extensions)

- Apex (.cls)

## Snippets

To use the snippets type part of a snippet and press `Tab` or `Enter` or, press `ctrl`+`Space` to activate instellisense.

### Apex Snippets

| Snippet                 | Description                            |
| ----------------------- | -------------------------------------- |
| `foreach`               | For-each loop                          |
| `ifelse`                | if/else statement                      |
| `ifnull`                | if statement null check                |
| `constructor`           | New constructor                        |
| `newobj`                | New Object                             |
| `field`                 | New field                              |
| `method`                | New method                             |
| `staticmethod`          | New static method                      |
| `sobjecttype`           | SObjectType for SObject                |
| `describesobjectresult` | DescribeSObjectResult for SObjectType  |
| `sobjectfield`          | SObjectField for SObject Field         |
| `describefieldresult`   | DescribeFieldResult for SObject Field  |
| `sysdebug`              | Debug Statement                        |
| `sysassf`               | System.assert(false, message);         |
| `sysasseq`              | System.assertEquals(expected, actual); |
| `sysassnull`            | System.assertEquals(null, actual);     |
| `sysassnotnull`         | System.assertNotEqual(null, actual);   |
| `mapids`                | Set Ids from map of SObject            |
