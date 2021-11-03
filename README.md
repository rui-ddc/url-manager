# url-manager

## Setup (for Ubuntu)
Download the **url-manager** file.<br />
Open a terminal and change directory to the current file location.<br />
Move the file to `/opt/scripts/` with the following commands:
```
sudo mkdir /opt/scripts/
```
```
sudo mv url-manager /opt/scripts/
```
Go to `Settings > Keyboard Shortcuts`.<br />
Create a *Custom Shortcut* with the following configuration:
```
Name:     url-manager
Command:  /opt/scripts/url-manager
Shortcut: Ctrl+u
```
You can now open url-manager by pressing <kbd>Ctrl</kbd> + <kbd>u</kbd>.

## Instructions
### Main Window
![main-window](https://github.com/rui-ddc/url-manager/blob/main/images/main-window.png)

Button | Action
-------| -------------------
Quit   | Quit URL Manager
Enter  | Open URL
Edit   | Edit Window

<br><br />

### Edit Window
![edit-window](https://github.com/rui-ddc/url-manager/blob/main/images/edit-window.png)

Button | Action
-------| -------------------
Back   | Main Window
Remove | Remove selected URL
Add    | Add Window

<br><br />

### Add Window
![add-window](https://github.com/rui-ddc/url-manager/blob/main/images/add-window.png)

Button | Action
-------| -------------------
Cancel | Edit Window
Ok     | Add new URL
