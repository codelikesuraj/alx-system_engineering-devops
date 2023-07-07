|Script file|Description|
|:-|:-|
|[0-iam_betty](0-iam_betty)|Switches the current user to the user 'betty'.|
|[1-who_am_i](1-who_am_i)|Prints the effective username of the current user.|
|[2-groups](2-groups)|Prints all the groups the current user is part of.|
|[3-new_owner](3-new_owner)|Changes the owner of the file 'hello' to the user 'betty'.|
|[4-empty](4-empty)|Creates an empty file called 'hello'.|
|[5-execute](5-execute)|Adds execute permission to the owner of the file 'hello'.|
|[6-multiple_permissions](6-multiple_permissions)|Adds 'execute' permission to the owner and the group owner, and 'read' permission to other user, to the file 'hello'.|
|[7-everybody](7-everybody)|Adds 'execute' permission to the owner, the group owner and the other users, to the file 'hello'.|
|[8-James_Bond](8-James_Bond)|Gives only other users all the permissions to the file 'hello' and no permission for owner and group.|
|[9-John_Doe](9-John_Doe)|Sets the mode of the file 'hello' to '-rwxr-x-wx'.|
|[10-mirror_permissions](10-mirror_permissions)|Sets the mode of the file 'hello' the same as file 'olleh's mode.|
|[11-directories_permissions](11-directories_permissions)|Adds 'execute' permission to all subdirectories of the current directory for the owner, the group owner and all other users.|
|[12-directory_permissions](12-directory_permissions)|Creates a directory 'my_dir' with permission '751' in the working directory.|
|[13-change_group](13-change_group)|Changes the group owner to 'school' for the file 'hello'.|
|[100-change_owner_and_group](100-change_owner_and_group)|Changes the owner to 'vincent' and the group owner to 'staff' for all the files and directories in the working directory.|
|[101-symbolic_link_permissions](101-symbolic_link_permissions)|Changes the owner and group owner of the symbolic link '\_hello' to 'vincent' and 'staff' respectively in the working directory.|
|[102-if_only](102-if_only)|Changes the owner of the file 'hello' to 'betty' only if it is owned by the user 'guillaume' in the working directory.|
|[103-Star_Wars](103-Star_Wars)|Plays the StarWars IV episode in the terminal.|
