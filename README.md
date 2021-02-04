# moodle-calendartype_ummulqora

A "calendartype" plugin for Moodle that will show the calendar dates as per Ummul Qora calculations.

## Installing UMMUlQura calendar

### Installing directly from the Moodle plugins directory
- Login as an admin and go to `Site administration > Plugins > Install plugins`. (If you can't find this location, then plugin installation is prevented on your site.)
- Click the button 'Install plugins from Moodle plugins directory'.
- Search for `UMMUlQura calendar`  with an Install button, click the Install button then click Continue.
- Confirm the installation request
- Check the plugin validation report

### Installing via uploaded ZIP file
- Go to the Moodle plugins directory, select your current Moodle version, then choose UMMUlQura calendar with a Download button and download the ZIP file.
- Login to your Moodle site as an admin and go to `Administration > Site administration > Plugins > Install` plugins.
- Upload the ZIP file. You should only be prompted to add extra details (in the Show more section) if your plugin is not automatically detected.
- If your target directory is not writeable, you will see a warning message.
- Check the plugin validation report

### Installing manually at the server
- Unzip the UMMUlQura calendar plugin in your moodle calendar/type folder. Now you can safely install the plugin.
- If you are already logged in with an admin account, just refreshing the browser should trigger your Moodlesite to begin the install 'Plugins Check'.
- If not then navigate to `Administration > Notifications`.

## Configuration
- To configure the default calendar select the the UMMUlQura calendar configuration from `Site adminstration / Appearance / Calendar`.
- Each user can also set their preferred calendar from the `Profile > Calendar` preference.

## Note
To see whether the plugin is successfully installed, navigate to the Plugins page in `Administration > Site Administration > Plugins > Plugins overview`, which lists all installed plugins together with the version number, release, availability (enabled or disabled) and settings link!

## Release logs

### Version 2021012501
* Added privacy API 
* Fix invalid parameter issue in calendar page
* Third party library for ummulQura calendar

