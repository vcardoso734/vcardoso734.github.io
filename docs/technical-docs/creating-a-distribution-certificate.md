---
layout: default
title: "Creating A Distribution Certificate (CER)"
parent: Creating Distribution Certificates and a P12 File
grand_parent: Technical Docs
nav_order: 2
typora-root-url: ../../
---

# Creating a Distribution Certificate (CER)

1. Log in to the Apple Developer site.
2. In the top navigation bar, click the **Account** link.
3. Click on the **Certificates, Identifiers & Profiles** tile.
4. Click the **+** button next to the Certificates title to create a new certificate.
   
   
   <img src="/files/images/dist-cert-1.png" alt="dist-cert-1" style="zoom: 33%;" />
4. Under the Software group, select the **iOS Distribution** (**App Store and Ad Hoc)** option and click **Continue**.

   <img src="/files/images/dist-cert-2.png" alt="dist-cert-2" style="zoom: 33%;" />

5. Click on **Choose File** and select the CSR file you created previously.
6. Click **Continue**.
7. Your distribution certificate is now ready. Click **Download** to save the CER file to your Downloads folder.
8. Move this file to the Distribution Files folder you created earlier.

**Next Step:** [Installing a Distribution Certificate]({% link docs/technical-docs/installing-a-distribution-certificate.md %})

