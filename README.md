# Salesforce Snippets for Salesforce (Apex) Development

[![Version](https://vsmarketplacebadge.apphb.com/version/lcotter.salesforce-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/lcotter.salesforce-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/lcotter.salesforce-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets)

Contains code snippets for Salesforce (Apex) for [Vs Code](https://code.visualstudio.com/) editor.

## Installation

1. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
1. Run `ext install Salesforce Snippets`

or

1. Search for [Salesforce Snippets](https://marketplace.visualstudio.com/items?itemName=lcotter.salesforce-snippets) in the extensions market place and install it.

## Supported languages (file extensions)

- Apex (.cls)

## Snippets

To use the snippets type part of a snippet and press `Tab` or `Enter`

or, press `ctrl`+`Space` to activate instellisense.

### Apex Snippets

| Snippet                 | Description                            |
| ----------------------- | -------------------------------------- |
| `foreach`               | For-each loop                          |
| `if`                    | if statement                           |
| `ifelse`                | if/else statement                      |
| `else`                  | else statement                         |
| `ifnull`                | if statement null check                |
| `while`                 | While loop                             |
| `dowhile`               | Do-While loop                          |
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
