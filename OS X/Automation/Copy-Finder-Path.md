# Copy folder path from Finder

## What do we want to achieve?
To right click a folder and copy its path from the Finder

1. Launch Automator
2. Create a new **Quick Action**
3. In the new workflow window, set **Workflow receives** to **files or folders** and set **in** to **Finder**
4. Add a new action called **Copy to Clipboard**
5. Save your workflow and it will be saved in ~/Library/Services
6. Right click on a folder in Finder and you will find your service with the name you provided. 
7. Clicking on that name will run your workflow and the folder / file path will be saved in your clipboard
