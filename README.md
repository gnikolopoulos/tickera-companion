# Wordpress Tickera companion
Wordpress plugin that extends the WP API to include endpoints for Tickera-related data. Provides access to ticket data. Comes with server and clients parts that can be installed in any website.
This plugin was created as a proof of concept and is provided as-is. Was originally created for a marathon races website, so it needs to be modified for each specific purpose.

## Server part
After install, add all the allowed hosts in the settings page. Then, for each host, set a unique token and assign any number of events the client app will be allowed access to. Also, set allowed functions per host.

## Client part
After install, add the token for your host (same as on the server part) as well as the Server host URL and save your settings. After refreshing the page, you will be presented with all the available shortcodes according to the events the server has allowed you access to.
