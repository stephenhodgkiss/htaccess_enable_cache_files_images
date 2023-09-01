# htaccess_enable_cache_files_images
htaccess commands to enable caching of files (js, css), images and video using mod_headers. 

Requires apache headers and expires to be enabled:

a2enmod headers
a2enmod expires
systemctl restart apache2
