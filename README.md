# java-cli-gradle-crypto-des-encrypted-scrypt-encoded

## Description
Encrypt and decrypt password with DES
encoded with scrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- java
- gradle
  - des
  - scrypt

## Docker stack
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
