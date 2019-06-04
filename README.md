# PayU IPN HMAC Signature Checker

PayU sends IPN notifications in order to confirm a new purchase with the Merchant system. These
messages need to be validated using a HMAC MD5 signature built by both parties using a shared secret 
key.

Use the form below to debug your IPN messages. You need your Secret Key from PayU and a request message
in a valid JSON format. The form is prefilled with a sample message.

**Warning!**

You can store your secret key and the json request to your local storage for easier debugging in the future,
but be aware that this way you may expose them to attackers.
