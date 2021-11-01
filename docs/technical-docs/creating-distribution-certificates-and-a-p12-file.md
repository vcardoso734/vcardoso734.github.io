---
layout: default
title: "Creating Distribution Certificates and a P12 File"
parent: Technical Docs
nav_order: 1
has_children: true
typora-root-url: ../../
---

# Creating Distribution Certificates and a P12 File

| About this example                                           |
| :----------------------------------------------------------- |
| *This article was for a former employer's online knowledge base. It explains how to create necessary files and certificates for iOS apps that are built by the company's publishing system.<br /><br />Customers who used the system were typically IT professionals without programming experience. Because of this, the documentation could be more sophisticated than something written for the average consumer, but still required detailed instructions on how to navigate the process.<br /><br />Tools used: ScreenSteps, Photoshop, Zendesk* |

## Introduction

You will need to generate several files before you can build and publish your app. This article walks you through creating a certificate signing request, a distribution certificate, and a P12 file.

### Important Terms

-  A **certificate signing request** contains encrypted data that identifies your Mac. It lets you obtain a distribution certificate from Apple.
- A **distribution certificate** identifies your team or organization. It ensures that your app has not been altered and lets you submit your app to the Apple App Store.
- A **P12 file** is an encrypted version of your distribution certificate. The mag+ Publishing Portal needs this file in order to build your app.

Warning
{: .label .label-red }

| *Distribution certificates are tied to the Mac where they are created. Perform these steps on the Mac that you will use to submit and publish your apps.* |

### Before You Begin

- Make sure you have signed up for an Apple Developer account.
- Identify which Mac you will use to submit apps to the Apple App Store.
- Create a Distribution Files folder on your Mac to keep all your certificates in one place.

