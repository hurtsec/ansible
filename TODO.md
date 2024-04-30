Figure out necessary steps to enable hardware key ssh on restart
  Theory:
    Need to turn on ssh-agent
    Need to ssh-add -K to add ssh key from hardware key

Create vars file to contain applications and utils referenced in ansible tasks to maintain parity between install and uninstall tasks
