---
pcx_content_type: how-to
title: Scoped API tokens
weight: 3
---

# Scoped API tokens

The administrators managing policies and groups in Cloudflare Access might be different from the users responsible for configuring firewall rules or other Cloudflare for Infrastructure settings. Cloudflare Access supports [scoped API tokens](https://support.cloudflare.com/hc/en-us/articles/200167836-Managing-API-Tokens-and-Keys) so that team members and automated systems can manage settings specific to Access without having permission to modify other configurations in Cloudflare.

## Creating a scoped API token

1.  In the [Cloudflare for Infrastructure](https://dash.cloudflare.com/) dashboard, click the user icon in the top right and navigate to "My Profile".

1.  Select the **API Tokens** tab. The existing tokens will display.

    ![Existing API tokens listed in the API Tokens tab.](/cloudflare-one/static/documentation/api-terraform/create-token.png)

1.  Click **Create Token**.

1.  Click **Get started** next to **Create Custom Token**.

1.  Select **Account** and **Access: Organizations, Identity Providers, and Groups** in the drop-downs under **Permissions**. You can configure the token to be Read or Write in the third drop-down.

    ![Dropdown displaying read and write options for API token customization.](/cloudflare-one/static/documentation/api-terraform/edit-token.png)

1.  In the final section, the token can be applied to a single account or multiple if you are an administrator of multiple Cloudflare accounts.

1.  Click **Continue to summary**. The next page will display the token details and instructions on how to use it.

## Review tokens

You can review tokens created in the **API Tokens** tab. In this view, you can roll, revoke, or edit issued tokens.

![A list of created API tokens.](/cloudflare-one/static/documentation/api-terraform/view-token.png)
