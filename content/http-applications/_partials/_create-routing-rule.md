---
_build:
  publishResources: false
  render: never
  list: never
---

To create a routing rule:

1. Log into the [Cloudflare dashboard](https://dash.cloudflare.com/login).
2. Select your account.
3. Go to **HTTP Applications**.
4. Select an existing application.
5. Click **Routing Rules**.
6. Click **Create Routing Rule**.
7. Fill out the following information:
    - **Rule name**: Provide a descriptive name.
    - **Rule Type**: Choose **Staging** or **Production** (**Staging** rules only run on requests sent to specific IP addresses).
    - **Zone(s)**: Select one or more zones to route traffic from.
    - **Application version**: Choose a version of your application to apply to the selected zones.
8. Click **Create**.