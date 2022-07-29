# 122

## heading 2- creata repo on github to clone to local host 
### heading 3 - testing the connection with http 

#### this change has been made locally 

# Installing python
- Python is developed under an open source license, making it freely usable and distributable, even for commercial use. 
- https://www.python.org/downloads/
- Follow installation path for your Operating System 
- 
# installing pycharm 
- PyCharm is a cross-platform IDE that provides consistent experience on the Windows, macOS, and Linux operating systems.
- PyCharm is available in three editions: Professional, Community, and Edu. The Community and Edu editions are open-source projects and they are free
- https://www.jetbrains.com/pycharm/download/#section=windows

[imag![pycharm](https://user-images.githubusercontent.com/104793540/181718158-d1351e9d-4441-4d0c-bc78-45709012c1a8.PNG)



- 
- 
- Download the installer .exe.
  To verify the integrity of the installer, use the SHA checksum linked from the Download page.
- Run the installer and follow the wizard steps.
    Mind the following options in the installation wizard
    64-bit launcher: Adds a launching icon to the Desktop.
    Open Folder as Project: Adds an option to the folder context menu that will allow opening the selected directory as a PyCharm project.
    .py: Establishes an association with Python files to open them in PyCharm.
    Add launchers dir to the PATH: Allows running this PyCharm instance from the Console without specifying the path to it.

To run PyCharm, find it in the Windows Start menu or use the desktop shortcut. You can also run the launcher batch script or executable in the installation directory under bin.


# installing git
- https://gitforwindows.org/
- 

# Signup to GitHub 
- https://github.com/
- Make an account to view global workflows and upload work from your local host so it too is available globally 
- 

# Workflow 
on local host do the following:
$mkdir foldername
$cd foldername/
$git clone httpslink
check with ls if repo cloned
cd clonedreponame
check with ls again 
cat README.md
nano README.md - make changes 
check content inside file with cat again to see if changes made 
git status 
git add .
git status 
git commit 
git push -u origin main 
