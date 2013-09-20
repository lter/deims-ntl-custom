deims-ntl-custom
================

Customizations for the NTL DEIMS migration

To use:

git clone  git@github.com:isangil/deims-ntl-custom

this is a custom Drupal 7.x module.  It extends the migrate and DEIMS D6 Migrate module
and it is ad-hoc for the particulars of the North Temperate Lakes LTER.

create a "modules" directory under  [path]/sites/default  (yes, not sites/all/modules).

place this module there, so you may have "sites/default/modules/deims-ntl-custom", or you
can also rename it "ntl", so you have "sites/default/modules/ntl".

Visit the modules page, and enable the NTL module.

Now visit the "migrate dashboard", if needed (like, nothing seems to change), Flush the
Class Registry cache, (use the admin toolbar, or use "drush cc") and then, re-register
the migration classes using the Migrate->Configuration page (admin toolbar, or from Migrate
Dashboard).  You should be game.
