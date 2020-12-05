# Open in Code

## Desired Solution

To right a folder and open in VS Code.

## Steps

1. Launch Automator
2. Select **Quick Action**
3. Select **Workflow receives current** folder in **Finder**
4. Add **Run Shell Script** action
5. Select your default Shell and set pass input **as arguments**
6. Run the following command in the textbox below **open -n -b "com.microsoft.vscode" --args "$*"**
7. Save