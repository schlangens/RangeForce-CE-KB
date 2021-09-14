# Command Prompt
- Computer systems balance many different tasks simultaneously
- Tasks are grouped into processes that run at various permission levels
- whoami: prints out the name of the user that is currently logged in
- id: shows additional details, including the user ID, the numberic value Linuxe uses to internally track access
- hostname: displays the machine's name, DNS Name, IP addr


# Privileges

# User Permissions
- Regular unprivileged user on linux can read most files and execute existing applications, but is generally prevented from making system-wide-changes or altering files owned by other uses
- etc/passwd: contains information users
- etc/shadow: contains hases that are used to authenticate users

# Authenticating with Sudo
- Elevating the normal user to root or super user privileges.
- Sudo -i: will changed the entire bash session from regular to super user


# Executing Remote Commands
- SSH