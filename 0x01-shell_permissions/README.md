1. # Shell Permissions

   This repository contains a collection of bash scripts that demonstrate various file and directory permission settings.

   ## Usage

   To use any of the scripts, you can simply execute them from the command line. For example:

   ```
   ./0-iam_betty
   ```

   This will change the user of the file to `betty`.

   ## List of Scripts

   1. `0-iam_betty`: changes the user of the file to `betty`.
   2. `1-who_am_i`: prints the effective username of the current user.
   3. `2-groups`: prints all the groups that the current user is part of.
   4. `3-new_owner`: changes the owner of the file to a specified user.
   5. `4-empty`: creates an empty file with specified permissions.
   6. `5-execute`: adds execute permission to a specified file.
   7. `6-multiple_permissions`: adds execute permission to the owner and group, and read permission to others.
   8. `7-everybody`: adds execute permission to the owner, group, and others.
   9. `8-James_Bond`: sets the file permissions to `007`.
   10. `9-John_Doe`: sets the file permissions to `753`.
   11. `10-mirror_permissions`: sets the file permissions of a specified file to be the same as another specified file.
   12. `11-directories_permissions`: sets directory permissions recursively.
   13. `12-directory_permissions`: creates a directory with specified permissions.
   14. `13-change_group`: changes the group of a specified file to a specified group.
   15. `14-chmod`: changes the file permissions of a specified file using octal notation.

