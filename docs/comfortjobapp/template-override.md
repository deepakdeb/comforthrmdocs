# How to Override Template


We have implemented woocommerce like template override system which means, you can override any template/view layer of this plugin in your theme. For this plugin, mainly admin interfaces of custom screens can be overridden. The frontend tour modals cannot be overridden as they load using JavaScript.

For core plugin: `wp-content/plugins/comfortjobapp/templates`  
For pro addon: `wp-content/plugins/comfortjobapppro/templates`

To override any file from your theme you have to create a folder called `comfortjobapp` inside your theme or child theme and copy files from the plugin’s template folder and put in this newly created folder inside your theme folder `comfortjobapp`. The process is same as the woocommerce theme file override.  


**Last modified:** December 9, 2024