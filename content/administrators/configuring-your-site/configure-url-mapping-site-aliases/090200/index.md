---
topic: configure-url-mapping-site-aliases
locale: en
title: Configure URL Mapping for Site Aliases
dnneditions: Platform,Evoq Content,Evoq Engage
dnnversion: 09.02.00
parent-topic: administrators-configuring-your-site-overview
related-topics: add-site-alias,edit-site-alias,delete-site-alias,change-primary-site-alias
---

# Configure URL Mapping for Site Aliases

## Prerequisites

*   **A host / super user account.** Hosts have full permissions to all sites in the DNN instance.

## Steps

1.  Go to Persona Bar \> Settings \> Site Settings.
    
    ![Persona Bar > Settings > Site Settings](img/scr-pbar-host-Settings-E91.png)
    
    ➊
    
    ➋
    
2.  Go to the Site Behavior tab, and then the Site Aliases subtab.
    
    ![Site Behavior > Site Aliases](img/scr-pbtabs-host-Settings-SiteSettings-SiteBehavior-SiteAliases-E90.png)
    
3.  Select the Site Alias Mapping Mode.
    
      
    
    ![Site Settings > Site Behavior > Site Aliases — Site Alias Mapping Mode](img/scr-SiteSettings-SiteBehavior-SiteAliases-MappingMode-E90.png)
    
      
    
    Option
    
    Description
    
    Canonical
    
    Recommended for SEO. Most useful when a page's content is dynamic or if the page contains a list that is split into multiple pages.
    
    Redirect
    
    Calls to non-primary site aliases are redirected to the primary site alias. The user sees the primary site alias in the browser's address field.
    
    None
    
    Site aliases are not mapped to any other site alias.
    
    Warning: This option can negatively affect your SEO score.
    
4.  (Optional) If available, enable Auto Add Site Alias.
    
    This option is available if you have only one site in the DNN installation. If enabled, DNN automatically extracts the site alias from the original page request and adds it to the list of aliases.
    
      
    
    ![Site Settings > Site Behavior > Site Aliases — Auto Add Site Alias](img/scr-SiteSettings-SiteBehavior-SiteAliases-AutoAdd-E90.png)
    
      
    
    Warning: Enabling this setting can be a security risk.