# firewall-cmd
firewall-cmd command

## add

````
firewall-cmd --zone=public --add-port=3306/tcp --permanent && firewall-cmd --reload
````

## remove

````
firewall-cmd --zone=public --remove-port=80/tcp --permanent && firewall-cmd --reload
````

## other command

````
firewall-cmd --zone=public --list-ports

firewall-cmd --zone=public --list-services

firewall-cmd --state

firewall-cmd --get-default-zone

firewall-cmd --add-service=http --permanent

firewall-cmd --reload

firewall-cmd --get-zones

firewall-cmd --get-active-zones

firewall-cmd --zone=public --list-all

firewall-cmd --list-all-zones

firewall-cmd --get-services
````
