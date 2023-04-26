# HMAC Code
Please proceed to the `sha256` folder in `week3`. Your job is now to compute HMAC and provide this to a receiver.

Your first need to compute the HMAC for the encrypted data `encrypted.user`. We provide a template code `template.py` but it has not finished yet. Your job is to complete this script and run. Once you run the file, you will get the HMAC for `encrypted.user` stored as `hmac.user` file.

Now your job is to send the HMAC to the receiver. You will use `launcher`. It will ask the filename of HMAC `hmac.user`, send it to the (virtual) receiver, and checks if the HMAC is the same as the HMAC that launcher will compute with `encrypted.user`.

If successful, you will get the flag.

Good luck!
