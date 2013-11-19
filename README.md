WP Jalapeno
======


Integrate DIA Salsa action forms seamlessly into your WordPress site.

[Plugin Website](http://www.wpjalapeno.com)

## Description

WP Jalapeno integrates your DIA Salsa actions with your WordPress site.  Install the plugin, enter in your Salsa
credentials, select your action and paste the relevant tag into your post or page.

You'll have the full power of DIA Salsa integrated into your WordPress site in a flash!

## Installation

1. After downloading the plugin, unzip the plugin.
2. Upload the `jalapeno` directory into your `wp-content/plugins` directory so that the structure is wp-content/plugins/jalapeno/....
3. Activate the plugin in the backend of your WordPress site.
4. Configure the plugin via the settings link that appears in the WP Jalape�o section of the left sidebar in the backend.

## Screenshots

1. Configure your connection to the Salsa servers.
2. The main configuration page for the action forms.  Drag and drop your desired fields to create the form.
   The following may be available as draggable fields, depending on how your action is configured in Salsa:
   * Supporter fields
   * Custom supporter fields
   * Action description
   * Action footer
   * One or more sets of content to be sent
   * Checkboxes for joining groups
   * Checkboxes to indicate whether to remain anonymous (for petitions)
   * Additional comments to submit (for petitions)
3. Embed a Salsa action form onto any page or post.
   You can either enter the tag directly, or you can click on the pepper icon to bring up a form to help you.
4. Two new sidebar widgets are available to you.
   One embeds a Salsa Action form anywhere in a sidebar, and the other shows the most recent signatures for a Salsa action.
   If you enable this, you should probably also allow supporters to sign anonymously so their name does not appear here.
   * Enable anonymous signatures in the action configuration within Salsa.
   * Refresh the action form in WordPress, and drag the anonymous checkbox into your form. 
5. An example of an action form in the sidebar, which also shows a list of the most recent signatures.
6. An example of an action form in the main content of a page.
7. Thank you for taking action, your comments have been emailed to the president!

## Changelog

### 1.0.3
1. Removing conflicting script with WordPress 3.3

### 1.0.2
1. Now supports WordPress 3.0
2. Disallow activation if PHP version < 5
3. Added support for restricted locations
4. New widget for rendering a form in the sidebar
5. New widget for rendering the most recent signatures
6. New field to make supporter anonymous
7. New field to provide optional comments
8. Provided default and help text for the host name config option
9. Added insert button to post editor
10. Added support for custom fields of the following types: text line, picklist, yes/no
  
### 1.0.1
1. Changed the name of the plugin
2. Added default CSS capabilities to apply to all forms
3. Changed the form insertion tag

### 1.0.0

1. Initial release
