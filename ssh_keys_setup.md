# How make a github repo use SSH keys for authentication

 SSH stands for Secure Shell. It's a cryptographic network protocol used for secure communication over an unsecured network. SSH allows users to securely log into remote systems and execute commands as if they were sitting directly at the remote computer. It provides strong authentication and encryption of data during transmission, making it a popular choice for remote administration and secure file transfer. SSH operates on TCP port 22 by default.

We do not want our repos to be public and be accessed by anyone. SSh auth ensure a secure way of accessing your repo.



## What are the steps  to do this?
+ Navigate to GitHub, sign in and create a repository or have one ready. 

![github](ssh.jpg)

* Create your SSH key
Use ssh-keygen to generate a public/private key pairing that you will use for authentication. You can type this in your terminal : 

```
ssh-keygen -t rsa -b 4096 -C "<your_email>"
```

* 