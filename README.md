# 122

## heading 2- creata repo on github to clone to local host 
### heading 3 - testing the connection with http 

#### this change has been made locally 

#### CREAT DIGITAL WOKFLOW AND INCLUDE HERE 

# Installing python
- Python is developed under an open source license, making it freely usable and distributable, even for commercial use. 
- https://www.python.org/downloads/
- ![image](https://user-images.githubusercontent.com/104793540/181721132-100b0042-ca03-4eb5-9ad5-5b9015ea2dc5.png)
- Follow installation path for your Operating System 

# Installing pycharm 
- PyCharm is a cross-platform IDE that provides consistent experience on the Windows, macOS, and Linux operating systems.
- PyCharm is available in three editions: Professional, Community, and Edu. The Community and Edu editions are open-source projects and they are free
- https://www.jetbrains.com/pycharm/download/#section=windows
- [imag![pycharm](https://user-images.githubusercontent.com/104793540/181718158-d1351e9d-4441-4d0c-bc78-45709012c1a8.PNG)


- Download the installer .exe.
  To verify the integrity of the installer, use the SHA checksum linked from the Download page.
- Run the installer and follow the wizard steps.
    Mind the following options in the installation wizard
    64-bit launcher: Adds a launching icon to the Desktop.
    Open Folder as Project: Adds an option to the folder context menu that will allow opening the selected directory as a PyCharm project.
    .py: Establishes an association with Python files to open them in PyCharm.
    Add launchers dir to the PATH: Allows running this PyCharm instance from the Console without specifying the path to it.

To run PyCharm, find it in the Windows Start menu or use the desktop shortcut. You can also run the launcher batch script or executable in the installation directory under bin.


# Installing git
- https://gitforwindows.org/
- ![image](https://user-images.githubusercontent.com/104793540/181721257-83018457-2540-4e03-a9fa-6997748f80fc.png)


# Signup to GitHub 
- https://github.com/
- Make an account to view global workflows and upload work from your local host so it too is available globally 
- ![image](https://user-images.githubusercontent.com/104793540/181722187-17232d33-41bb-4092-8e3c-f0c237dab97b.png)


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
