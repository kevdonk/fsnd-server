# fsnd-server

IP Address: 52.39.168.4

SSH Port: 2200

URL: http://52.39.168.4/portfolio


### Software Installed
I mostly went through installing the packages that the Vagrantfile for my app required ( https://github.com/kevdonk/fsnd-catalog/blob/master/Vagrantfile#L30 ).

### Config Changes
I made the config changes suggested in the course.

I changed the SSH port to 2200.

I set up UFW to only allow connections on 2200, 80, and 123.

I disabled password logins, and root login.

I add the `grader` user to sudoers.d.

### Resources used
https://www.godaddy.com/help/changing-the-ssh-port-for-your-linux-server-7306

https://askubuntu.com/questions/709843/how-to-configure-ufw-to-allow-ntp-to-work

https://askubuntu.com/questions/311558/ssh-permission-denied-publickey

https://unix.stackexchange.com/questions/229431/why-are-all-my-ssh-attempts-failing-due-to-timeout

https://mediatemple.net/community/products/dv/204643810/how-do-i-disable-ssh-login-for-the-root-user

https://askubuntu.com/questions/138423/how-do-i-change-my-timezone-to-utc-gmt
