# Run_Script_On_NanoStartup

# Create a bash script that runs what you like it to run. 

# Modify its permissions
```bash
sudo chmod 777 ...path of startup bash script...
```

# Go to etc/sudoers file and modify it so that it does not require password entry for certain users

```bash
jetson ALL=(ALL) NOPASSWD: ALL 
```

# Open the Startup Application and use the following startup command

```
gnome-terminal -x ...path to startup script...
```
