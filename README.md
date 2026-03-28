# How to use this image



## Matomo Installation

Once you're up and running, you'll arrive at the configuration wizard page. If you're using the compose file, at the `Database Setup` step, please enter the following:

- Database Server: `db`
- Login: MYSQL_USER
- Password: MYSQL_PASSWORD
- Database Name: MYSQL_DATABASE

And leave the rest as default.

Then you can continue the installation with the super user.

The following environment variables are also honored for configuring your Matomo instance:

- `MATOMO_DATABASE_HOST`
- `MATOMO_DATABASE_ADAPTER`
- `MATOMO_DATABASE_TABLES_PREFIX`
- `MATOMO_DATABASE_USERNAME`
- `MATOMO_DATABASE_PASSWORD`
- `MATOMO_DATABASE_DBNAME`

The PHP memory limit can be configured with the following environment variable:

- `PHP_MEMORY_LIMIT`
