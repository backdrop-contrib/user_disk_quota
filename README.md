# User Disk Quota

## CONTENTS OF THIS FILE

 * Overview
 * Features
 * Supported modules
 * Installation
 * How to use
 * How to use with Views
 * How to use with Quote
 * License

### OVERVIEW

The User Disk Quota module allows to limit user disk quota per single user or
per user's role.

### FEATURES

Each user could be limited on the total size of uploadable files.
The limit could also be set per user role. The uploaded file by user, by design, works only for file uploaded using a Backdrop form.
FTP uploaded size could not be counted on disk quota total size.

### SUPPORTED MODULES

 * Views
 
### INSTALLATION

1. Copy the User Disk Quota folder to the modules folder in your    installation.
2. Enable User Disk Quota folder modules using Administration -> Modules(/admin/modules).
3. Set module's permissions using People -> Permissions (admin/people/permissions).
4. Configure user roles' limit using People -> Disk quota (admin/people/disk-quota).
5. (Optional) Configure disk quota limit for single users on every user edit page.

### License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

### Maintainers

This project was originally written for Drupal by: 
* [Alberto Colella](http://drupal.org/user/460740)
* http://drupal.org/user/460740/contact
* kongoji@gmail.com

Ported to Backdrop by:
* Jerad Bitner (http://github.com/sirkitree)
