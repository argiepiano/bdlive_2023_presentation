# Using hooks to extend Backdrop CMS
## Presentation for Backdrop Live - September 2023

This repo contains a demo module to illustrates the use of hooks in Backdrop CMS.

The hooks covered in this presentation are:
- `hook_form_FORM_ID_alter()`
- `hook_node_view_alter()`
- `hook_node_insert()`, `hook_node_update()`, `hook_node_delete()`
- `hook_permission()`
- `hook_menu()`
- `hook_field_widget_form_alter()`
- `hook_block_view_alter()`
- `hook_views_pre_render()`
- `hook_action_info()`
- `hook_install()`
- `hook_entity_info_alter()`

Upon installation, this module will also:
- Create two new roles
- Create a new taxonomy vocabulary
- Create a few terms for the new vocabulary
- Create two users and assign them roles (NOTE: the password is hard-coded in the example. This may constitute a security risk if you install this module online.)
- Create three views.

To access the slides for the presentation, follow [this link](https://docs.google.com/presentation/d/1eGNGdowVDIsfaZ1SekM3bRrII2btpx-55oQfy_fZ2ZY/edit?usp=sharing)

## Credits
Created by [argiepiano](https://github.com/argiepiano) for Backdrop Live September 2023.
