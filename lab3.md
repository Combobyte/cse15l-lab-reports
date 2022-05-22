# Lab report 3

---

Hello! Welcome to lab 3 where we will talk about all of the 3 special activites from last week.

1. The first activity was streamlining ssh configuration

    a) Below we can see my ssh config file. I edited this file using `vi config` but showed it using `cat config`.

    ![Image](imageslab3/config.png)

    b) Now we can see that I am able to log in using just `ssh ieng6`

    ![Image](imageslab3/ssh.png)

    c) Now we can also use `scp` without having to type too much:

    ![Image](imageslab3/scp.png)

2. The second activity was making it so you could commit from the terminal on the cs15l account.

    a) Here is the screenshot of my pulic key on Github:

    ![Image](imageslab3/sshkeyongithub.png)

    b) And now we can see that the private key in on my user account in the .ssh folder:

    ![Image](imageslab3/wheredarsa.png)

    c) Here is me commiting and pushing on the user account. The link to the commit is [Here](https://github.com/Combobyte/markdown-parser/commit/05721a1014069e9122691325f8606f43e0e34bf5)

    ![Image](imageslab3/gitpush.png)

3. The third activity was copying full directories to the user account.

    a) we can use `scp -r` to copy the whole directory:

    ![Image](imageslab3/justcopy.png)

    b) We can then go onto the course specific account and run the tests:

    ![Image](imageslab3/make.png)

    c) We can also see that we are able to copy and run in one step using the command `scp -r markdown-parser ieng6:~/; ssh ieng6 "cd markdown-parser; make test`. The image doesn't show the run because of the amount of files being copied, but it did run the test:

    ![Image](imageslab3/copyandrun.png)

Thanks for reading!