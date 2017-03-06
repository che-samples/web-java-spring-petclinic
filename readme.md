[![Test Beta](http://codenvy.io/factory/resources/codenvy-contribute.svg)](https://a2.codenvy-stg.com/f?name=demo-ic&user=slemeur)

Thanks for participating into our beta review of new intelligent commands features.

## Command Explorer
A new commands explorer is available from the left panel bar - below the project explorer.
Click on "Commands" to display the commands explorer.
Commands are regrouped by goals to provide a clearer organization and an easier navigation into the commands list.

## Command Editor
From the commands explorer you can double click on a command to open it in the new command editor.
The new command editor:
- provides more space for command authoring
- allows multi-line commands 
- makes it simpler to access command's macros
- allows to configure applicable context for commands

## Command Toolbar
The command toolbar allow a quick view and access to all the executed commands.
When you start a command, the commands is automatically displayed in the command toolbar.
It displays:
- the targeted machine for the command
- the command's name
- the time since the command has been started
It also allows you to stop a command or re-start a command.

If you click on the command toolbar, you'll have all the commands that you executed in your workspace displayed in a list. You can select one to see its output displayed in the processes panel. 

## Run and Debug buttons
"Run" and "Debug" buttons allow you to select a command which is defined in those goals. 
When you have multiple commands, you can default the one that will be executed on click on one of those buttons. To change the default commands associated with the "Run" or "Debug" button, do a long click to see available options.

## Preview button
The preview button, allows to get the list of all your running servers on your workspace's machines.
For example, when your command start tomcat and has a previewURL associated, the previewURL will be accessible from this button.

## Command palette
Try the new command palette from `Run> Command Palette` or using the keyboard shortcut `shift+F10`
You can search into the list of commands and use the keyboard to navigate into the list and start the command.


# Provide your feedback
We particularly appreciate your time to test those new capabilities. 
Please send us your feedbacks, they are welcomed! You can send them to the contact who invite you to the beta review or to slemeur@codenvy.com

We have number of enhancements that we are working on:
- Related to UI + UX + first experience: https://github.com/eclipse/che/issues/4295
- Providing better identifiers for previewURL: https://github.com/eclipse/che/issues/4273
- Better handling of screen's width: https://github.com/eclipse/che/issues/4272
