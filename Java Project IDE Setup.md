# Java Project IDE Setup

## Steps To Use Java Project

### In Eclipse

- Create empty folder on the desktop for Eclipse Workspace to start 
- Choose **Checkout projects from Git**
- Select **Repository Source as Clone URI**
- Provide the **URI of the Git** repository and **Login details** (Make sure to check the `[x]` Store in Secure Store)
- Select **Branch Name** and **Directory Location** for Git to download it locally
- Select **Import existing Eclipse Project** and Finish
- Miscellaneous Setup:
  - Editor Font Size (Settings > Search "Font" > Appearnce > Java > Java Editor Text Font) - 14
  - Editor Console Font Size (Settings > Search "Font" > Appearnce > Basic > Text Font) - 12
  - Perspective:
    - Left Column - Top: Package Explorer, Bottom: Console
    - Middle Column - Editor
    - Right Column - Outline
- Import Competitive Programming Formatter by clicking Preferences button, followed by `Java > Code Style > Formatter > Import`
  - File - [Java_Competitive_Programming_Eclipse_Formatting_Settings.xml](https://github.com/abhinavg916/git-and-github/blob/master/Java_Competitive_Programming_Eclipse_Formatting_Settings.xml)

### In VSCode

- Git clone the project to the local machine
- Install `Extension Pack for Java` by Microsoft in VSCode
- Locate and Open the folder of the Java Project in VSCode
- Let the extension detect and run the code
