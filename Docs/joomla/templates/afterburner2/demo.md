---
title: Afterburner2: Recreating the Demo
description: Your Guide to Recreating Elements of the Afterburner2 Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/afterburner2:Afterburner2

---

Introduction
-----

![][afterburner2]

Recreating features of the demo site used to show off some of the more interesting aspects of Afterburner2 can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Afterburner2 Template.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the Template's core files in order to make them easily accessible without having to edit any code.

Module Settings
-----

Like any Gantry template, Afterburner2 allows you to assign modules to specific positions within selected overrides. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][Afterburner22]

:   1. **Frontpage Showcase**  [12%, 9%, se]
    2. **Popular Features (Article)**  [34%, 10%, se]
    3. **Template Extras (Article)**  [49%, 10%, se]
    4. **Preset Styles**  [34%, 66%, se]
    5. **Module Variations**  [50%, 66%, se]
    6. **Demo Information** [76%, 10%, se]
    7. **Contact Us** [76%, 66%, se]

We have detailed how to recreate the individual modules and features pictured above in the links below.

1. [Frontpage Showcase][module1]
2. [Popular Features (Article)][module2]
3. [Template Extras (Article)][module3]
4. [Preset Styles][module4]
5. [Module Variations][module5]
6. [Demo Information][module6]
7. [Contact Us][module7]

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Afterburner2:

* [Gantry Template Framework][gantry]
* RokCommon Library (Installed with RokSprocket)
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

All of these extensions are included with the Afterburner2 RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Afterburner2 demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Afterburner2 template.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Afterburner2 - Home** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. Under the **Main Menu** list, you will want to select **Home** in the Menu Assignments tab..

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple key changes in order for your home page to appear as it does in our demo.

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to `Afterburner2 — Free, GPL Template`.

[gantry]: http://gantry-framework.org/download
[afterburner2]: assets/afterburner22.jpeg
[afterburner22]: assets/afterburner2.jpeg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/extensions-joomla/roknavmenu
[rokbooster]: http://www.rockettheme.com/extensions-joomla/rokbooster
[module1]: demo_module_1.md
[module2]: demo_module_2.md
[module3]: demo_module_3.md
[module4]: demo_module_4.md
[module5]: demo_module_5.md
[module6]: demo_module_6.md
[module7]: demo_module_7.md
[module8]: demo_module_8.md
[module9]: demo_module_9.md
[module10]: demo_module_10.md
[module11]: demo_module_11.md
[module12]: demo_module_12.md
[module13]: demo_module_13.md
[module14]: demo_module_14.md
[module15]: demo_module_15.md
[mainmenu]: assets/menu_1.jpeg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[scroll]: assets/demo_2.jpeg