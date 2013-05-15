This is a port of the drupal 6 user import domain module to Drupal 7.

MODULE:
User import domain access Groups Module

DESCRIPTION:
Allows users to be assigned domains when using the user import module.
New and existing users can be mass assigned to domains by importing
data from a CSV file.

********************************************************************
PREREQUISITES:

  - User Import module
  - Domain access module 

********************************************************************
INSTALLATION:

Note: It is assumed that you have Drupal up and running.  Be sure to
check the Drupal web site if you need assistance.

1. Place the entire directory into your Drupal directory:
   sites/all/modules/

2. Enable the user_import, domain & user_import_domain modules by
   navigating to:
   administer > build > modules

  Click the 'Save configuration' button at the bottom to commit your
  changes. 

********************************************************************
PERMISSIONS:

Set access permissions for which role(s) can use this feature at
 - Administer > User management > Permissions (admin/user/permissions)

Permissions:
* Administer user import domain - This allows users to access the
domain settings on the user import configuration screen
(admin/user/user_import/configure)
* Import to any domain - Users who have this permission will be able
to assign imported users to any domain.  Otherwise they can only
import users into domains they are a member of. 

********************************************************************
AUTHOR CONTACT:

- Report Bugs/Request Features:
   http://drupal.org/project/user_import_domain

- Commission New Features:
   http://drupal.org/user/89106/contact

********************************************************************
ACKNOWLEDGEMENT:

Developed by Agileware (www.agileware.net)
