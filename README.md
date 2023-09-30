# ERPNext Guide

If you are here, you must be stupid, its a simple setup you moron.

## SQL Setup

You need to create a mariadb server `11.1.2-MariaDB` and make sure the below config is set

`bind-address = 0.0.0.0`

You have to set this in the config file which you can find with `mysql --help`

## Frappe Setup

You can comment the `db:` build when using the mysql on local or uncomment when using mysql within docker

## Start the app

Use `docker-compose -f ./pwd.yml up` to run the app.

### Conclusion

If you still can get it up, give up! You cant do it ever!
Its bad enough you have to write this just incase you might need it in the future
