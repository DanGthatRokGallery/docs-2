---
title: RokGallery: Editing and Managing Image Files
description: Your Guide to Working with Images Using RokGallery for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/rokgallery:RokGallery

---

Image Editing in RokGallery
-----
RokGallery is not a full-fledged image editing solution, but it can be used to crop and resize images so that they fit within your site's layout. Because RokGallery preserves the original image, these edits are saved separately and referred to as slices. A single image in RokGallery can have as many slices as you need to fit various RokGallery modules placed in your site. These slices can be created by the RokGallery Image Editor and further refined using the Slice Editor.

### RokGallery Image Editor

The RokGallery Image Editor is available to you from within the RokGallery component administration interface found in **Administrator -> Components -> RokGallery**. By clicking on an image's edit icon **(1)**, a panel appears which gives you direct access to the image's title, slug (URL-friendly title), description, tags, and its slices.

![][rokgallery_image_editor_2]

:   1. **Edit Icon** Grants access to an image's editing panel. [38%, 12%, nw]
    2. **Title** This field allows you to adjust the image's title as needed. [50%, 5%, se]
    3. **Slug** This field is for the url-friendly slug for the image, replacing spaces with dashes. This field is automatically generated by RokGallery, however you can change it as needed. [62%, 20%, sw]
    4. **Description** You would enter the description of an image here. [74%, 5%, se]
    5. **Tags** You can add and remove tags to the particular image in this area. [50%, 33%, se]
    6. **Slices** This area of the Image Editor is where you can access the Slice Editor to create new slices, edit existing ones, generate a sharable link to a slice, or delete the slice. The Admin Thumbnail is a default slice used on the administrative side of RokGallery to display the image on the backend and can not be deleted. [50%, 61%, se]

1. **Edit Icon**: Grants access to an image's editing panel.

2. **Title**: This field allows you to adjust the image's title as needed.

3. **Slug**: This field is for the url-friendly slug for the image, replacing spaces with dashes. This field is automatically generated by RokGallery, however you can change it as needed.

4. **Description**: You would enter the description of an image here.

5. **Tags**: You can add and remove tags to the particular image in this area.

6. **Slices**: This area of the Image Editor is where you can access the Slice Editor to create new slices, edit existing ones, generate a sharable link to a slice, or delete the slice. The Admin Thumbnail is a default slice used on the administrative side of RokGallery to display the image on the backend and can not be deleted.

### RokGallery Slice Editor

#### Administrative Slices
![][rokgallery_slice_editor]

:   1. **Admin Slice Indicator** A red bookmark in the upper-left area of the Slice Editor indicates that the selected slice is used for administrator purposes only, and can not be deleted. [18%, 6%, nw]

1. **Admin Slice Indicator** A red bookmark in the upper-left area of the Slice Editor indicates that the selected slice is used for administrator purposes only, and can not be modified or deleted.

#### Regular Slices
![][rokgallery_slice_editor_2]

:   1. **Grip** This tool allows you to grab and move a zoomed-in image around in the editor. [38%, 6%, nw]
    2. **Select** This tool gives you the option to select a specific area within the image to crop for the slice. [35%, 10%, sw]
    3. **Zoom Controls** These controls allow you to zoom in, zoom out, and view the image in the original size. [38%, 15%, nw]
    4. **Marquee** This control gives you the current position of the selection area, as well as the ability to set a specific location. [38%, 30%, nw]
    5. **Width and Height** This option allows you to set a specific width and height for the selection area. This option is disabled on administrative slices. Once applied, the selected area is cropped to become the new or edited slice. [38%, 41%, nw]
    6. **Size** The size settings allow you to do a simple resize of the image. You can adjust these settings even when there is a lock icon over the numbers, but changes will only be completed upon hitting the **Apply** button. This is not an option on administrative slices. [38%, 53%, nw]
    7. **Revert and Apply** These buttons allow you to revert all settings to the original image, or apply any changes made. You still need to hit **Save** **(10)** before closing the slice to save all changes, though. [38%, 62%, nw]
    8. **Title, Slug, Link, Caption, and Tags** These options allow you to change the title, slug, link (where clicking the image takes the visitor), caption, and the slice's tags independently of defaults set in the Image Editor. [9%, 16%, sw]
    9. **Thumbnail** This option sets the thumbnail size for the slice as it would appear in any gallery displays that require a thumbnail. Additionally, these settings are used on the administrative end to display the slice in the Image Editor. [12%, 65%, se]
    10. **Save, Publish, Gallery, and Close** These options allow you to save the slice as it has been edited in the Slice Editor, as well as publish the slice, assign a gallery (tags), and close the Slice Editor. If you wish to exit the Slice Editor without saving anything you have done, just hit **Close**. [12%, 85%, nw]

1. **Grip**: This tool allows you to grab and move a zoomed-in image around in the editor.

2. **Select**: This tool gives you the option to select a specific area within the image to crop for the slice.

3. **Zoom Controls**: These controls allow you to zoom in, zoom out, and view the image in the original size.

4. **Marquee**: This control gives you the current position of the selection area, as well as the ability to set a specific location.

5. **Width and Height**: This option allows you to set a specific width and height for the selection area. This option is disabled on administrative slices. Once applied, the selected area is cropped to become the new or edited slice.

6. **Size**: The size settings allow you to do a simple resize of the image. You can adjust these settings even when there is a lock icon over the numbers, but changes will only be completed upon hitting the **Apply** button. This is not an option on administrative slices.

7. **Revert and Apply**: These buttons allow you to revert all settings to the original image, or apply any changes made. You still need to hit **Save** **(10)** before closing the slice to save all changes, though.

8. **Title, Slug, Link, Caption, and Tags**: These options allow you to change the title, slug, link (where clicking the image takes the visitor), caption, and the slice's tags independent of the defaults set in the Image Editor.

9. **Thumbnail**: This option sets the thumbnail size for the slice as it would appear in any gallery displays that require a thumbnail. Additionally, these settings are used on the administrative end to display the slice in the Image Editor.

10. **Save, Publish, Gallery, and Close**: These options allow you to save the slice as it has been edited in the Slice Editor, as well as publish the slice, assign a gallery (tags), and close the Slice Editor. If you wish to exit the Slice Editor without saving anything you have done, just hit **Close**.

The Slice Editor gives you the ability to edit (or create) individual slices used in gallery modules and other RokGallery-supported areas of your site. These slices are independent copies of the original images, and as such, any changes you make in the Slice Editor only affect the individual slice.

[rokgallery]: assets/rokgallery.jpeg
[rokgallery_component]: assets/rokgallery_component_1.jpeg
[rokgallery_component_configuration_options]: assets/rokgallery_component_configuration_opions.jpeg
[rokgallery_component_upload]: assets/rokgallery_component_upload.jpeg
[rokgallery_image_editor]: assets/rokgallery_image_editor.jpeg
[rokgallery_image_editor_2]: assets/rokgallery_image_editor_2.jpeg
[rokgallery_jobs_manager]: assets/rokgallery_jobs_manager.jpeg
[rokgallery_module_1]: assets/rokgallery_module_1.jpeg
[rokgallery_module_advanced]: assets/rokgallery_module_advanced_1.jpeg
[rokgallery_module_basic_1]: assets/rokgallery_module_basic_1.jpeg
[rokgallery_module_error_1]: assets/rokgallery_module_error_1.jpeg
[rokgallery_plugin_manager_1]: assets/rokgallery_plugin_manager_1.jpeg
[rokgallery_plugin_manager_2]: assets/rokgallery_plugin_manager_2.jpeg
[rokgallery_plugin_manager_3]: assets/rokgallery_plugin_manager_3.jpeg
[rokgallery_administrator]: assets/rokgallery_administrator.jpeg
[rokgallery_tags]: assets/rokgallery_tags.jpeg
[rokgallery_galleries_manager]: assets/rokgallery_galleries_manager.jpeg
[rokgallery_slice_editor]: assets/rokgallery_slice_editor.jpeg
[rokgallery_slice_editor_2]: assets/rokgallery_slice_editor_2.jpeg