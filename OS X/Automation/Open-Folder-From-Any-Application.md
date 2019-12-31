# How to open a folder from any application via keyboard shortcut

## What do we want to achieve?
To open a folder with a keyboard shortcut from any application. 

1. Launch Automator
2. Create a new **Quick Action**
3. In the new workflow window, set **Workflow receives** to **no input**
4. Add a new action called **Get Specified Finder Items** and add the folder path that you want it to open
5. Add another action called **Open Finder Items** and set **Open with** to **Default Application**
6. Running the action will open the folder. 
7. Save your workflow and it will be saved in ~/Library/Services
8. Open **System Preferences** -> **Keyboard** -> **Shortcuts** and select **Services** from the left hand menu
9. Find workflow under the **General** section. 
10. Click on the **none** to add a keyboard shortcut. The shortcut you select needs to be unique to your system.
11. After setting a keyboard shortcut, the shortcut may not work right away. From any application, from the menubar go to **services**, find your shortcut and click on it. 
12. The keyboard shortcut should now work across all applications. 
