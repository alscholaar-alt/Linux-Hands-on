## Level 15 - 16

***Aim:*** Submit the level 15 password on port 30001 using SSL/TLS encryption.

- The command that is used as a toolkit that implements the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols is `openssl`.
- the openssl command needs to followed by a 'tool' to let it know what to do which in this case is `s_client` which works as a client to establish a connection with the server you are looking to connect with.
- The command is made in the format of `openssl s_client -connect host:port`

Action taken:

- I established a secure connection to `localhost` on port `30001` then inserted the password.

```bash
openssl s_client -connect localhost:30001
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```

***Level 16 Password:*** `kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx`

<img width="254" height="80" alt="Screenshot 2026-01-27 at 10 36 05" src="https://github.com/user-attachments/assets/3d04445f-8215-453a-a868-84a5cada8046" />
