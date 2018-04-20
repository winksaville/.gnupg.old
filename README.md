# The gnu pgp directory

This is the default .gnupg file for key 0x9F79B9CEB03232F9. The
encrypted keys are obviously not here but are stored on a yubikey.

I followed [this article](https://blog.eleven-labs.com/en/openpgp-almost-perfect-key-pair-part-1/) to setup the initial gpg keys and
[this article](https://blog.eleven-labs.com/en/openpgp-secret-keys-yubikey-part-2/)
to setup the yubikey.

To use clone this repo to .gnupg and change mode to 700:
```
$ git clone git@github:winksaville/.gnupg .gnupg
$ chmod 700 .gnupg
```
Then insert the yubikey and use card-status the
yubikey and .gnupg are working.
```
$ gpg --card-status
...
```
