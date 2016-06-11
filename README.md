diaspora_ynh
==========

Diaspora integration for YunoHost

Notes
--------------

Before installing, you have to:

- get a dedicated domain (must install under web root like **https://diaspora.example.com/** not **https://example.com/diaspora/**)
- get a valid SSL certificate
  - can use [letsencrypt](https://letsencrypt.org/) with this fun [app](https://github.com/alexAubin/letsencrypt_ynh) of alexAubin :)
  - or more hard, can use [startssl.com](https://www.startssl.com/)

Installation effects:

- Thank you for being patient as deployment time can take up to about 2 hours.
- The installation directory can take up to 700MB and app start time can be take 5 minutes.

Make yourself (your account) an admin:
- https://wiki.diasporafoundation.org/FAQ_for_pod_maintainers#What_are_roles_and_how_do_I_use_them.3F_.2F_Make_yourself_an_admin_or_assign_moderators

Not implement yet:

- backup and restart scripts.
