---
order: 5
pcx-content: tutorial
---

import CaptivePortals from "../_partials/_captive-portals.md"

# iPhone

Follow this quick guide to start using 1.1.1.1 on your iPhone.

<StreamVideo id="ddf07732bc76fc854d4b1879eea2c517"/>

1. Go to **Settings**.
1. Click on **Wi-Fi**.
1. Click the information **'i'** icon next to the Wi-Fi name you are connected to.
1. Scroll down until you see the section called **Configure DNS**.
1. Change the configuration from **Automatic** to **Manual**.
1. Click **Add Server**.
1. Remove any IP addresses that may be already listed and in their place add:

    ```txt
    1.1.1.1
    1.0.0.1
    2606:4700:4700::1111
    2606:4700:4700::1001
    ```

1. Click **Save**.

## Using DNS Override iOS App

You can also use a handy iOS app called DNS Override (paid app, costs $1.99) that automatically configures 1.1.1.1 for you on any network you connect to. To use it:

<StreamVideo id="da4eefaa9315767842737eb793c9b63d"/>

1. [Download DNS Override from the app store](https://itunes.apple.com/us/app/dns-override/id1060830093?mt=8).
1. Launch the DNS Override app.
1. Click **1.1.1.1** at the top of the app.
1. Turn on the **DNS Override** toggle.
1. DNS Override may ask you to install their VPN profile so that they can automatically update DNS settings.

<CaptivePortals/>
