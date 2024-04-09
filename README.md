moodle-local_custom_error
=========================

Displays custom error pages.

Set Up
------
1. This should be installed in the local directory of the Moodle instance.
2. Install the plugin via Moodle Administration and set the custom error text in settings
3. Update you apache configuration (httd.conf) to include the following
   > ErrorDocument 404 /local/custom_error/view.php?error=404
4. Restart Apache service

Test
----
Go to a URL which does not exist and view the content