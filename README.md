
This is a sample Android app project showing how to tokenize the card using [Simplify's Hosted Payment](https://simplify.com/commerce/docs/tools/hosted-payments) feature in a WebView.
Hosted Payments supports varieties of features including card number & expiry validation, and authentication flows such as 3DS.

After the card is tokenized, the token can be used to complete the payment using any of the SDKs offered by Simplify Platform - https://simplify.com/commerce/docs/sdk/index

For the sake of convenience, we have provided an example file [hostedPayment.php](./hostedPayment.php) in this repo. This file needs to be hosted on your server. Please make sure to update the correct API Keys in that file.

The embedded WebView listens for the redirect for `simplify://cardToken?=` scheme and parses the URL for the card token.


![](/assets/hosted-payment-demo.gif)

**License**

Apache License, version 2.0.

© Copyright 2019
