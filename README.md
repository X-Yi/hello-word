# hello-word
How to avoid being asked passphrase each time when doing git push?
Answer: you need to use an ssh agent.
* *ssh-add*

if "Could not open a connection to your authentication agent." appear

then try
* *eval $(ssh-agent)*

then again
* *ssh-add*
