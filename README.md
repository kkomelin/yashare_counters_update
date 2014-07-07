## Yandex.Share with Counters Update


There is a problem with Yandex.Share with Counters field (https://github.com/paulanders/yashare_counters).
If you add Yandex.Share with Counters field to a content type it won't display counters for existing nodes.
Previously you had to update the nodes manually to make Yandex.Share with Counters field visible.

Now you have this module. It allows you to update necessary fields of chosen content type.
The module uses Batch API to process big number of nodes.
Moreover, it doesn't call heavy node_save() and updates necessary fields only.


###DEPENDENCY
------------------------------------------------------------------------------
- https://github.com/paulanders/yashare_counters


###USAGE
------------------------------------------------------------------------------
1. Backup your database!
2. Install module.
4. Go to the admin/config/development/yashare_counters_update page.
4. Press the "Update all" button and wait. Waiting time can depend on quantity of nodes on your site.
But you will see current progress. Thanks for it to Drupal Batch API.
5. Check node content.
6. Profit.


###DEVELOPER
------------------------------------------------------------------------------
Konstantin Komelin https://github.com/konstantin-komelin
