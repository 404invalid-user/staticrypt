# StatiCrypt


Based on the [crypto-js](https://github.com/brix/crypto-js) library, StatiCrypt uses AES-256 to encrypt your string with your passphrase in your browser (client side).

Download your encrypted string in a HTML page with a password prompt you can upload anywhere (see [example](http://invaliduser.uk.to/staticrypt/example.html)).

You can encrypt a file online at http://invaliduser.uk.to/staticrypt.

## HOW IT WORKS

**Disclaimer** if you have extra sensitive banking data you should probably use something else!

StatiCrypt generates a static, password protected page that can be decrypted in-browser: just send or upload the generated page to a place serving static content (github pages, for example) and you're done: the javascript will prompt users for password, decrypt the page and load your HTML.

It basically encrypts your page and puts everything with a user-friendly way to use a password in the new file.

AES-256 is state of the art but brute-force/dictionary attacks would be trivial to do at a really fast pace: **use a long, unusual passphrase**.

The concept is simple but I am not a cryptographer, feel free to contribute or report any thought to the GitHub project! (Though be warned it might take me a long time to get to it - I apologize in advance)

Similar project: [MaxLaumeister/clientside-html-password](https://github.com/MaxLaumeister/clientside-html-password)

## Owner 
I do not own this I have made some changes to the html and css to make it look nicer 
You can go to the original one here https://robinmoisson.github.io/staticrypt/
