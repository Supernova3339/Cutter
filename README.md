# CursoRDP 
**Instructions**
-
CRD Editions
-------
Go to actions. If workflows aren't enabled, enable them.

Go to a CRD Edition page.

Go here https://remotedesktop.google.com/access and get a command. Depending on OS, you need a special one. Windows is PowerShell and Ubuntu is Debian. When it is on Keep Alive, check Chrome Remote Desktop computers. Connect to the one that is marked on "Online" and enter then pin you put while running the workflow.

If you are on ubuntu make sure to select "LXQT Desktop" on the menu.


RDP Edition
-------
Go to actions. If workflows aren't enabled, enable them.

Go to RDP Edition.

Sign up or login to NGRok and get your authtoken at https://dashboard.ngrok.com/get-started/your-authtoken

When it is on "Starting RDP", go to "Endpoints", refresh your page if needed and copy the link on the left w/out tcp:// **RDP credentials are given inside the workflow run.**


NoVNC Edition
-------
Go to actions. If workflows aren't enabled, enable them.

Go to NoVNC Edition.

No prerequisites are required, as it uses PGRok. The default link is novnc01.ejemplo.me, but this can be changed in the yaml in .github/workflows.

**Extra Info**
-------
Installation time can take up to 5 minutes, usually takes around a minute.

Ubuntu NoVNC uses a docker container, for fast start times. This also means it doesn't have any of the host software. Please take note of this if you are modifying this.

Ubuntu NoVNC's link can be modified. Go to .github/workflows, open it's YAML and change the --subdomain novnc01 to --subdomain (your subdomain)

These expire after roughly 6-7 hours. These are not 24/7.

**Info**
-------
This version is 4.2




