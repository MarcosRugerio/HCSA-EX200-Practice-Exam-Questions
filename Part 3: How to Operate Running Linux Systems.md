## Task 1: Reset Root Password
- Break into node2 and set a new rootpassword to hoppy

## Task 2: Tuninig Profile Configuration and SELINUX
- Check the current recommended tuning profile.
- Put SELINUX in **permissive** mode on node2.
- on node1 ensure network service is enabled and starts on boot

## Task 3: Persistent Journaling
- Configure persistent journaling on **both servers** to retain logs across reboots.

## Task 4: Process Scheduling
- Start a stress-ng process on node1 with a niceness value of **19**.
- Adjust the niceness value of the running stress-ng process to **10**.
- Terminate the stress-ng process.

## Task 5: File Permissions & File ACLs
- Copy /etc/fstab to /var/tmp
- Set the file owner