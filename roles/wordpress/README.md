# Wordpress Role

## Role Variables

| Name         | Description   | Default                 | Required |
| ------------ | ------------- | ----------------------- | :------: |
| domain_name  | hostname      | `wp.com`                |    no    |
| app_name     | app name      | `wordpress`             |    no    |
| php_fpm_sock | php-fpm.sock  | `/run/php/php-fpm.sock` |    no    |
| sites_path   | home dir      | `/var/www/html`         |    no    |
| db_name      | database name | `wordpress`             |    no    |
| db_host      | database host | `localhost`             |    no    |
| db_user      | database user | `wordpressuser`         |    no    |
| db_pass      | database pass | `wordpresspass`         |    no    |
