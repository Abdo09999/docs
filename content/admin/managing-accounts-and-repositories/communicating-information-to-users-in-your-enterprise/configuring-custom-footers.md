---
title: Configuring custom footers
intro: 'You can give users easy access to enterprise-specific links by adding custom footers.'
permissions: Enterprise owners can configure a custom footer.
versions:
  ghec: '*'
  ghes: '*'
type: how_to
topics:
  - Enterprise
  - Fundamentals
shortTitle: Configure custom footers
redirect_from:
  - /admin/configuration/configuring-your-enterprise/configuring-custom-footers
---

## About custom footers for your enterprise

You can configure the web UI for your enterprise to display a custom footer with up to five additional links. The custom footer appears above the default {% data variables.product.prodname_dotcom %} footer{% ifversion ghes %}, to all users and on all pages of {% data variables.location.product_location_enterprise %}{% elsif ghec %} to all enterprise members and collaborators, on all repository and organization pages for repositories and organizations that belong to the enterprise{% endif %}.

## Configuring custom footers

{% data reusables.enterprise-accounts.access-enterprise %}
{% data reusables.enterprise-accounts.settings-tab %}
1. Under **{% octicon "gear" aria-hidden="true" aria-label="gear" %} Settings**, click **Profile**.
1. At the top of the page, under the navigation bar, click **Custom footer**.

   ![Screenshot of the "Profile" page for an enterprise account. A tab, labeled "Custom footer", is outlined in dark orange.](/assets/images/enterprise/custom-footer/custom-footer-section.png)
1. Under each "Footer Link" heading, type a title and URL.
1. To save the content and display the custom footer, click **Update custom footer**.
