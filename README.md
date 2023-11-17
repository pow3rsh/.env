## Symmetic encryption

For symmetic encryption, you can use the following:

To encrypt:

    openssl aes-256-cbc -salt -a -e -in plaintext.txt -out encrypted.txt

To decrypt:

    openssl aes-256-cbc -salt -a -d -in env.enc -out env.tar.gz
