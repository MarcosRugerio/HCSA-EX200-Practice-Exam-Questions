## Task 1: Size-Based file search
- Create a shell script that:
1. Finds files in the /usr sized >30KB but <50KB
2. Outputs results to /root/sized_files.txt

## Task 2: Conditional Script (career.sh) with argument
Create /root/career.sh that:
1. Outputs "Yes, I'm a Systems Engineer." when run ./career.sh me
2. Outputs "Okay, they do cloud engineering." when run with ./career.sh they
3. Outputs "Usage: ./career.sh me|they" for invalid/empty

## Task 3: File processing, input/output User and Groups Scripts.
Write shell scripts on node1 that create user and groups according the following parameters

maryam:2030:hpc_admin,hpc_managers
adam:2040:sysadmin,
jacob:2050:hpc_admin

Write a shell script that sets the passwords of the users maryam, adam and jacob to Password@1