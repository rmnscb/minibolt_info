# MiniBolt Info

A bash script to monitor a [MiniBolt node](https://v2.minibolt.info/home/readme) health and activity at a glance.

## Installation
 ```sh
  $ sudo apt install jq net-tools netcat
  $ cd /tmp/
  $ git clone https://github.com/rmnscb/minibolt_info.git 
  $ cd /tmp/minibolt_info/
  $ nano *.sh --linenumbers # Inspect the scripts to make sure it does not do bad things. Exit with Ctrl-X
  $ sudo chmod +x *.sh  # Install the script and make it executable
  $ sudo cp *.sh /usr/local/bin/
  ```
## Disable admin password request (optional -caution!)
[how to disable admin password request](https://v2.minibolt.info/bonus-guides/system/ssh-keys#disable-admin-password-request-optional-caution)

