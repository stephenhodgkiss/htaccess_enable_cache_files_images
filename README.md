# htaccess enable cache of files, images and media

htaccess commands to enable caching of files (js, css), images and media using mod_headers. 

Requires apache headers and expires to be enabled:

a2enmod headers
a2enmod expires
systemctl restart apache2
