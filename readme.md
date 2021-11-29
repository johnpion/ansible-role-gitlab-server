# Ansible Role "Gitlab"

Ansible role for configuring Gitlab

## system
OS: Debian

## vars
* gitlab_email_display_name
* gitlab_email_enabled
* gitlab_email_from
* gitlab_external_url (may be undef)
* gitlab_letsencrypt (bool)
* gitlab_nginx (bool)
* gitlab_nginx_ssl
  * path
  * domain
* ldap_dn
* ldap_enabled (boot)
* ldap_identify (uid, sAMAccountName, etc)
* ldap_password
* ldap_server
* ldap_user
