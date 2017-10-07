# mycards
Add, remove, or print simple cards. Cards are stored either in a shared folder (for all users) or in an internal user folder.

* This is still under development. Not ready to be used.

To do:

* Implement the option to delete cards.

* In the case of adding a card, check whether the user included a full path. Only a file name should be provided, without a path. Another option is to accept a full path, but in that case the path should be removed before checking if the file exists in the standard directories.

* Add the option to be installed by an user without root privileges.

* Check the current user before looking for the personal mycards directory. For now, the user is called "runner".
