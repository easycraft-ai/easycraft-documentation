---
title: "Chapter 4: Login Management"
sidebar_position: 4
---

# Chapter 4: Login Management

## 4.1 Login Configuration
Users can either use the system’s default login template or create a custom one.
For example, configuring the background image of the portal login page, embedding quick access to applications on the login page, changing the logo, adjusting the login box layout, etc.

The specific steps are as follows:
1. Enter the portal backend management, select the "Login Management - Login Configuration" menu, and in the login page list, click "Create" on the right, as shown below:
2. Enter the login template selection interface.
3. Preview the styles of various login templates, then select [Use Template] in the upper right corner.
4. After entering the login page name, click "OK" to enter the login page configuration page.
5. Configure the login box information, content information, and background information of the login page, then click [Save] in the upper right corner.
   - Tip: After saving the configuration, you can preview the effect. If it is not suitable, close the preview and adjust the configuration directly for efficient configuration.
6. Close the configuration, return to the login page list, select the configured login page, and click the "Use" button.
7. When users enter the system login page, the display effect is as follows:
   - Tip: The mobile login page configuration is the same as the desktop version.

## 4.2 Pop-up Notifications
Configure the login pop-up. After publishing, you need to wait for the background scheduled task (executed hourly) to run before users can see the pop-up content when logging in.

The specific steps are as follows:
1. Go to Login Management - Pop-up Notifications, click "Create" on the right, and select a pop-up template.
2. Enter the pop-up title and content in the preview area on the left, modify the font, text color, pop-up background image, etc., and preview the effect directly.
3. After selecting a pop-up template, enter the pop-up configuration page. The configuration area on the right allows you to set basic information such as pop-up frequency, notification scope, notification time, recipients, and style. The pop-up will notify the specified people within the set time range according to the configured frequency.
   - Tip: Remember to fill in the notification time; otherwise, the pop-up will not appear.
4. Return to the pop-up list and publish the newly created pop-up.
   - When the pop-up maintainer field is empty, everyone can maintain it. After specifying a person, only the specified person and the creator can maintain it.
   - Newly published pop-ups will take effect after 1 hour. If you want it to take effect immediately, switch to the system administrator account and manually execute the "Login Pop-up Scheduled Task." After execution, click to view the scheduled task details and check the logs to see if it was successful.
5. Switch to a regular account to log in and view the pop-up.
