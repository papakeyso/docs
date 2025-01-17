---
title: Enterprise administrator documentation
shortTitle: Enterprise administrators
intro: 'Documentation and guides for enterprise administrators, system administrators, and security specialists who {% if enterpriseServerVersions contains currentVersion %}deploy, {% endif %}configure{% if enterpriseServerVersions contains currentVersion %},{% endif %} and manage {% data variables.product.product_name %}.'
introLinks:
  overview: '{% if enterpriseServerVersions contains currentVersion %}/admin/overview/system-overview{% elsif currentVersion == "github-ae@latest" %}/admin/overview/about-github-ae{% endif %}'
changelog:
  label: enterprise
featuredLinks:
  guides:
    - '{% if currentVersion == "github-ae@latest" %}/admin/overview/managing-billing-for-your-enterprise{% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/user-management/auditing-users-across-your-enterprise{% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/configuration/restricting-network-traffic-to-your-enterprise{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/admin/configuration/configuring-backups-on-your-appliance{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/admin/enterprise-management/creating-a-high-availability-replica{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/admin/enterprise-management/upgrading-github-enterprise-server{% endif %}'
  guideCards:
    - '{% if currentVersion ver_gt "enterprise-server@2.22" %} /admin/github-actions/getting-started-with-github-actions-for-github-enterprise-server {% elsif currentVersion ver_lt "enterprise-server@3.0" %} /admin/enterprise-management/upgrading-github-enterprise-server {% endif %}'
    - '{% if currentVersion ver_gt "enterprise-server@2.22" %} /admin/packages/getting-started-with-github-packages-for-your-enterprise {% elsif currentVersion ver_lt "enterprise-server@3.0" %} /admin/user-management/customizing-user-messages-for-your-enterprise {% endif %}'
    - '{% if currentVersion ver_gt "enterprise-server@2.22" %} /admin/configuration/configuring-advanced-security-features {% elsif currentVersion ver_lt "enterprise-server@3.0" %} /admin/installation/setting-up-a-staging-instance {% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/configuration/initializing-github-ae{% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/user-management/customizing-user-messages-for-your-enterprise{% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/github-actions/getting-started-with-github-actions-for-github-ae{% endif %}'
  popular:
    - '{% if currentVersion == "github-ae@latest" %}/admin/release-notes{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/github/getting-started-with-github/setting-up-a-trial-of-github-enterprise-server{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/admin/installation{% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/authentication/configuring-authentication-and-provisioning-for-your-enterprise-using-azure-ad{% endif %}'
    - '{% if currentVersion == "github-ae@latest" %}/admin/overview/about-upgrades-to-new-releases{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/admin/overview/managing-your-github-enterprise-license{% endif %}'
    - '{% if enterpriseServerVersions contains currentVersion %}/admin/configuration/command-line-utilities{% endif %}'
    - /admin/enterprise-support/about-github-enterprise-support
layout: product-landing
versions:
  enterprise-server: '*'
  github-ae: '*'
children:
  - /overview
  - /installation
  - /configuration
  - /authentication
  - /user-management
  - /policies
  - /enterprise-management
  - /github-actions
  - /packages
  - /enterprise-support
  - /advanced-security
  - /guides
  - /release-notes
  - /all-releases
---
