[![Build Status](https://travis-ci.org/andeersg/medium_publish.svg)](https://travis-ci.org/andeersg/medium_publish)

Medium Publish
-------
This module allows you to publish/export your content to Medium.com.


Configuration
--------------------------------------------------------------------------------
 1. On the People Permissions administration page ("Administer >> People >> Permissions") you need to assign:
    - The "Administer Medium settings" permission to the roles that are allowed to
      access the Medium publish admin pages, edit application settings and add/edit
      configs.

    - The "Publish to Medium" permission to the roles that are allowed to publish their
    nodes to their Medium accounts.

 2. The main administrative page controls the settings for the different content
    types. It is possible to add, edit, disable and delete configs:
      admin/config/content/medium_publish

 3. The integration can be configured from the settings page:
      admin/config/content/medium_publish/settings
