# Impact Tracker Pre-Installed Version

This is a version of the Impact Tracker which is already set up and ready to use, allowing you to skip the installation steps at [https://github.com/cirlabs/impact-tracker](https://github.com/cirlabs/impact-tracker). It's **very important** that you update the admin user email address and password for security.

The Impact Tracker is built on Drupal 7, which uses PHP and MySQL.

## Installation

1. Create a database and import the `database.db` file.
2. Configure the database connection in `sites/default/settings.php`. Look for the `$database` array at line 247.
3. Visit the site and log in with username `admin` and password `ChangeMe%AReH5A=`.
4. **IMPORTANT**: Update the admin user e-mail address and password by clicking the "Account" link in the navigation bar then clicking on the edit tab.
5. **IMPORTANT**: Update the site e-mail address by navigating to Configuration > System > Site Information. ([your_site]/admin/config/system/site-information)
