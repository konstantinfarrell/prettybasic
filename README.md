# Pretty Basic Template

A pretty basic template for html and javascript based projects. Includes jQuery 2.2.4 and Angular 1 as well as bootstrap.

For all those situations where you want to start a project, but really hate starting projects.

## Install

Just edit this apache vhost config file and you're good to go.

Edit `prettyfancy.conf.example` and place it in your vhost directory.
Remember to remove the `.example` extension once its all set up.
Then restart the service.

    vim prettyfancy.conf.example
    cp prettyfancy.conf.example /etc/httpd/vhost.d/prettyfancy.conf
    systemctl restart httpd

