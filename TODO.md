- remove fonts.css from the ubuntu-html5-theme repo
- patch handlebars so that partials have a proper identation
- check url for updates
- generate all icon sizes based on the biggest one
- copy js files (or r.js to build folder)
- grunt task to change the vhosts on MAMP and restart apache
    subl /private/etc/hosts
    subl /Applications/MAMP/conf/apache/extra/httpd-vhosts.conf
    /Applications/MAMP/bin/apache2/bin/apachectl restart