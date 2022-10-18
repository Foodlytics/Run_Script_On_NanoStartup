# Run_Script_On_NanoStartup

1. Create a bash script that runs what you like it to run. 

2. Modify its permissions
```bash
sudo chmod 777 ...path of startup bash script...
```

3. Go to etc/sudoers file and modify it so that it does not require password entry for certain users

```bash
jetson ALL=(ALL) NOPASSWD: ALL 
```

4. Open the Startup Application and use the following startup command

```
gnome-terminal -x ...path to startup script...
```
