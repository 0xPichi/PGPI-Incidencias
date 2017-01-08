-- SUMMARY --

'view own' module adds 'view own <content-type> content' and 
'view any <content-type> content'  permissions for all of content types. 
'view own' and 'view any' so natural in context of 'edit own', 'edit any'
permissions which provided by node module. Also view_own do not need any
additional tables to database.

For a full description visit the project page:
  http://drupal.org/project/view_own
Bug reports, feature suggestions and latest developments:
  http://drupal.org/project/issues/view_own

-- REQUIREMENTS --

None.

-- INSTALLATION --

* Install as usual, see http://drupal.org/node/70151 for further information.
* Or visit <your-installation>/admin/build/modules

-- CONFIGURATION --

* Configure user permissions in Administer >> User management >> Permissions
  >> view_own module:

  - do not forget add 'view any <content type> content' permissions for 
    'authenticate user' role if you want to allow  authenticate users to
    see apropriate content type

-- CONTACT --

Current maintainers:
* Vadim Potapenko (djuba) - vadim.potapenko@gmail.com

This project has been sponsored by:
* E2E4
  Specialized in web development. Visit http://www.e2e4gu.ru for more information.


