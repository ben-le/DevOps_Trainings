### User and Group Management

#### Users

In Linux and Unix-like operating systems, users are individuals who interact with the system. Each user has a unique username and numeric user ID (UID), which are used to identify them within the system. Here’s an overview of user management:

1. **Creating Users:**
   - To create a new user, use the `useradd` command:
     ```bash
     sudo useradd -m username
     ```
     This command creates a new user with the specified username and creates a home directory (`-m` option).

2. **Setting Passwords:**
   - Set a password for the user using `passwd`:
     ```bash
     sudo passwd username
     ```
     Follow the prompts to set the password securely.

3. **Modifying Users:**
   - To modify user attributes, use `usermod`. For example, to add a user to a supplementary group:
     ```bash
     sudo usermod -aG groupname username
     ```
     This adds the user to the specified group without modifying other group memberships (`-a` option).

4. **Deleting Users:**
   - To delete a user and optionally remove their home directory, use `userdel`:
     ```bash
     sudo userdel -r username
     ```
     The `-r` option removes the user’s home directory and mail spool.

#### Groups

Groups in Linux allow users to be categorized together, simplifying access control and resource management. Each group has a unique group name and numeric group ID (GID). Here’s how group management works:

1. **Creating Groups:**
   - Create a new group using the `groupadd` command:
     ```bash
     sudo groupadd groupname
     ```
     This creates a new group with the specified groupname.

2. **Adding Users to Groups:**
   - Add a user to a group using `usermod`. This example adds the user to a supplementary group:
     ```bash
     sudo usermod -aG groupname username
     ```
     Replace `groupname` with the group to add the user to, and `username` with the user’s username.

3. **Managing Group Membership:**
   - To list the groups a user belongs to, use `groups`:
     ```bash
     groups username
     ```
     This displays all groups the user `username` is a member of.

4. **Deleting Groups:**
   - Remove a group using `groupdel`:
     ```bash
     sudo groupdel groupname
     ```
     This deletes the group `groupname`. Ensure no users depend on this group before deletion.

User and group management is fundamental for maintaining security, access control, and organizational structure within a Linux system. By understanding these concepts and commands, administrators can effectively manage user privileges and system resources.
