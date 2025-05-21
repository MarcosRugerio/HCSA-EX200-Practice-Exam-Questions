## Task 1: Text search & Archive - Man pages
1. Find the string "Listen" in /etc/httpd/conf/httpd.conf and save the output to /root/web.txt
2. Create a gzip-compressed tar archive of /etc named etc_vault.tar.gz in /vaults directory

## Task 2: File links - Shortcuts
1. In /shorts directory:
- Create a file file_a
- Create soft link file_b pointing to file_a
- Create hard linkg file_c pointinh to file_a
- Verify all links work

## Task 3: Advanced File Operations - Find
1. Find files in /usr that are greater than 3MB but < 10MB and copy then to /bigfiles directory.
2. Find files in /etc modified more than 120 days ago and copy then to /var/tmp/twenty/
3. Find all files owned by user hadoga and copy  them to /root/h-files
4. Find a file name "httpd.conf" and sabe the absolute parths to /root/httpd/paths.txt

## Task 4: Remote Access & File Permissions
1. From node1, SSH into node2 as user hadoga and:
2. Copy the contents of /etc/fstab to /var/tmp
3. Set the file ownership to root
4. Ensure no execute permissions to anyone.
