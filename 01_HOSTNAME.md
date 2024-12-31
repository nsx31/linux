## Check the hostname : 
```sh
$ hostname
```

## Location where hostname is stored : 
```sh
$ cat /etc/hostname
```

## Setting up hostname of server or workstation :
```sh
$ sudo hostnamectl set-hostname <new_host_name>
```

## Updating the /etc/hosts file
- The `hostnamectl` command will not update the /etc/hosts file automatically when we change the host name instead we have to manually do it.
- Use any text editor and update the file.
```sh
$ sudo nano /etc/hosts
```

