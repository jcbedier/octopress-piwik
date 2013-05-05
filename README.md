octopress-piwik
===============
This settings permits to add piwik support for octopress blog.
+ _config.yml.patch show the two settings you should add to your ``_config.yml``
+ Copy ``source/_includes/after_footer.html`` into your ``source/_includes`` (please look at your after_footer.html you'll see that there is just an insert of : ``{% include piwik_analytics.html %}``
+ Copy ``source/_includes/piwik_analytics.html`` into your ``source/_includes`` folder

## piwik_url
Depends of your piwik URL.
Example:
+ piwik.mydomain.com
+ mydomain.com/piwik

## piwik_siteid
SiteID provide by piwik when you add a new sites.
