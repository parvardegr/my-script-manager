# Linux Script Manager
    - Don't keep your bash scripts in a repository?😱
    - Do it with my-script-manager today!

Manage your day to day or work linux bash scripts as a git repository 😍 with command line tool to auto update and sync your machine. 💘

With my-script-manager you can share your scripts between your devices and with your friends and colleagues, easily setup your new devices, keep track of your scripts and never lost them again.

    💌 Help this project evolve by your contributin.

# Usage

1. fork this repositry

2. clone your respository in a nice location (ex: /opt)

3. `cd {clone-location}/my-script-manager`

4. load scrits: `sudo ./scriptmanager --load`

5. open new terminal or logout from existing

6. add your scripts in project root directory (see: example), don't forget `sudo chmod +x your-new-script`

7. push your changes

8. sync scripts: `scriptmanager --sync`

9. [optional] add --sync cronjob: `scriptmanager --cron`

10. access and use your scripts from any machine just by clone it in seconds!

11. enjoy your nice scripts!

## scriptmanager tool
```bash
Script Manager v0.1

Usage:
	scriptmanager [COMMAND]

Commands:
	--sync: pull from origin and sync scripts
	--load: init my-script-manager and add scripts to PATH (use .profile)
	--cron: add cronjob to --sync each 5 minutes
	--help: show this message
```