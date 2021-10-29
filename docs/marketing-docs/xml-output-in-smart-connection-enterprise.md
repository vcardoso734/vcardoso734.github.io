---
layout: default
title: "XML Output in Smart Connection Enterprise"
parent: Marketing Docs
nav_order: 3
typora-root-url: ../../
---

# XML Output in Smart Connection Enterprise
{: .no_toc }

| About this example                                           |
| :----------------------------------------------------------- |
| *At the time this article was written, many system administrators wanted to know how to export files stored within the Smart Connection Enterprise CMS as XML. I created this fact sheet for salespeople to send to potential customers.<br /><br />Tools used: Adobe InDesign, Adobe Acrobat* |

WoodWing's Smart Connection Enterprise (SCE) system offers several options for exporting articles in XML format. System administrators can perform a manual export, set up a Smart Mover export, or program a PHP Event Handler export.

<details open markdown="block">
  <summary>
    Contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Manual Export

When used with Adobe’s InCopy word processor, SCE stores InCopy articles in XML format with WoodWing-specific modifications.

Customers can choose to export one or more articles manually by using the SCE server’s **Export Article** command. This exports a raw InCopy file, complete with all InCopy styling and markup.

<img width ="50%" src="/files/images/manual-export-1.png" />

## Smart Mover

WoodWing's Smart Mover is a general purpose file automation and transformation application with a GUI interface. It processes files unattended according to a schedule set by the system administrator. Articles in SCE can be exported as:

- **InCopy XML:** The raw InCopy file, complete with all InCopy styling and markup.
- **SCE XML:** A file containing the article’s SCE metadata and story contents in plain text.
- **Minimal XML:** A version of the native InCopy file with minimal styling applied.

Smart Mover also has a number of other features to automate file export and transformation. It can perform text substitutions (with regular expression support), transform XML files via XSLT, and transmit files via HTTP REST.

## Event Handler

Event Handler is a PHP method delivered as a standalone file that taps into the SCE's business logic layer. Instead of operating on a timed schedule (like Smart Mover), it watches events on the SCE server and immediately responds with custom actions. Event Handler is capable of:

- Exporting files.
- Compressing files using the ZIP compression method.
- Generating a clean XML output that is customized to a client’s needs.

A sample Event Handler is available from WoodWing USA that can output articles in a simplified XML format. Knowledge of the PHP programming language is required in order to modify the export.

