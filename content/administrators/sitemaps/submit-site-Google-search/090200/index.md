---
topic: submit-site-Google-search
locale: en
title: Submit Your Site to Google Search for Indexing
dnneditions: Platform,Evoq Content,Evoq Engage
dnnversion: 09.02.00
parent-topic: administrators-sitemaps-overview
related-topics: configure-sitemap
links: ["[Google: Setting Up Event Tracking](https://developers.google.com/analytics/devguides/collection/gajs/eventTrackerGuide?csw=1)"]
---

# Submit Your Site to Google Search for Indexing

## Prerequisites

*   **A host / super user account.** Hosts have full permissions to all sites in the DNN instance.

## Steps

1.  Go to Persona Bar \> Settings \> SEO.
    
    ![Persona Bar > Settings > SEO](img/scr-pbar-host-Settings-E91.png)
    
    ➊
    
    ➋
    
2.  Go to the Sitemap Settings tab.
    
      
    
    ![SEO Sitemap settings](img/scr-SEO-SiteMapSettings-TitleGeneral-E90.png)
    
      
    
3.  Submit your sitemap's URL to Google for indexing.
    1.  Choose Google from the Search Engine dropdown. Click/Tap Submit.
        
          
        
        ![Site Submission > Search Engine](img/scr-SEO-SiteMapSettings-Submission-SearchEngine-E90.png)
        
          
        
        You will be directed to the Google Search Console page in a new browser tab.
        
    2.  Log in with your Google account.
    3.  In Google's Search Console, enter the URL to your site and Submit Request.
        
          
        
        ![Site URL Submission](img/scr-GoogleSearchConsoleSubmitURL-small.png)
        
          
        
4.  Verify that you own the site.
    1.  Go to the [Google Webmasters Tools](https://www.google.com/webmasters/tools/home) page.
    2.  Choose Website from the dropdown and enter the URL to your site. Click/Tap Add a Property.
        
          
        
        ![Site URL Submission](img/scr-GoogleSearchConsoleSubmitURL-big.png)
        
          
        
        You will be directed to a set of instructions for Recommended method and Alternate methods.
        
    3.  Go to the Recommended method tab (HTML file upload) and copy the filename provided by Google.
        
          
        
        ![Site URL Submission](img/scr-GoogleSearchConsole-VerificationFile.png)
        
          
        
    4.  In the DNN Sitemap Settings page, in the Site Submission section, paste the filename to the Verification field, and click/tap Create.
        
          
        
        ![Site Submission > Verification](img/scr-SEO-SiteMapSettings-Submission-Verification-E90.png)
        
          
        
    5.  In the Google Verification page, click/tap Verify.
        
          
        
        ![Site URL Submission](img/scr-GoogleSearchConsole-Verify.png)