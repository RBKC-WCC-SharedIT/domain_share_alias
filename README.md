This module allows multiple domains on a single Domain Access Drupal instance to use the same aliases. 
It does this by creating a new url_alias table for each domain, using the domain_[domain id]_url_alias 
table naming pattern.

The code was copied from https://www.drupal.org/node/1953292


