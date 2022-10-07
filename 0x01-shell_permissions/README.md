[su user] change the user ownership
[whoami or id -un] show the effective username of the current user
[$ groups or id -Gn] prints all the groups the current user is part of
[sudo chown user file] change the file ownership
[touch ] create a empty file
[chmod u+x file ] adds execute permission to the owner of the file
[chmod u+x,g+x,o+r file] adds execute permission to the owner and the group owner, and read permission to other users
[chmod --reference= file file1 file]Copy File Ownership to Another File
[chmod -R a+X *]  execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
[chown owner:group owner /u ]change_owner_and_group

