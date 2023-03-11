# Passwd_Gen
This is a password generator written in bash just to test how shell scripting works.
Here is a breakdown of the command:

"openssl" refers to the OpenSSL library, which provides cryptographic functions and tools.

"rand" is the command within OpenSSL used to generate random bytes.

"-base64" specifies that the output should be encoded in Base64 format. Base64 is a method for encoding binary data using only printable ASCII characters.

"48" specifies the number of random bytes to be generated. Since each byte contains 8 bits, 48 bytes equals 384 bits of random data.
The length of the password will help cutting down the generated sequence.
