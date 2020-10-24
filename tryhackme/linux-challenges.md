1) SSH into the virtual machine.
    - `ssh garry@10.10.30.112`
    - How many visible files can you see in garrys home directory?
      - 3 
        - How I got this: Simple `ls` command while in the home directory.
        
* * *

1) What is flag 1?
    - f40dc0cff080ad38a6ba9a1c2c038b2c
      - How I got this: I used the `cat` command on `flag1.txt`
2) Log into bob's account using the credentials shown in flag 1. What is flag 2?
    - 8e255dfa51c9cce67420d2386cede596
      - How I got this: I used `ssh` with the login credentials then I used the `cat` command on flag2.txt
3) Flag 3 is located where bob's bash history gets stored.
    - 9daf3281745c2d75fc6e992ccfdedfcd
      - How I got this: I used the `history` command to find the flag. The flag was the first entry. 
4) Flag 4 is located where cron jobs are created.
    - dcd5d1dcfac0578c99b7e7a6437827f3
        - How I got this: I had to research on cronjobs. Found the command `cronttab -e`

      
    
