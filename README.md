# paperwallet.telestai.io
JavaScript Client-Side Telestai Wallet Generator

Now Telestai addresses and their corresponding private key can be conveniently 
generated in a web browser.

The Telestai project (telestai.io) provides an all-in-one HTML document with embedded
JavaScript/Css/Images. The JavaScript is readable not minified and contains no
XMLHttpRequest's (no AJAX). The benefit of this technique is you can load the 
JavaScript locally and trust that the JavaScript did not change after being 
loaded. 


Please send DONATIONS for this project to Bitcoin Address (original developer): 
1NiNja1bUmhSoTXozBRBEtR8LeF9TGbZBN

**Procedure for Importing a Paper Wallet into the QT Wallet:**

1) Perform a clean installation on a system without any previous wallet (ensure the absence of the .telestai directory). Prior to deletion, safeguard your seed words.

2) Run ./telestaid in one terminal window.

3) In another terminal window, execute ./telestai-cli importprivkey "MY-PRIVATE-KEY-GENERATED-ON-PAPER-WALLET".

4) Close the ./telestaid window (CTRL-C).

5) Open the QT wallet, set a passphrase, allow it to synchronize for a few minutes, and start enjoying your wallet.

END USER NOTES:

 1) For Bulk Wallet I recommended using Google Chrome, it's the fastest.

 2) Requires IE9+, Firefox, Chrome or sufficient JavaScript support.

 3) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.

 4) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.

 5) BIP38 most likely will not work on mobile devices due to hardware limitations.


Notice of Copyrights and Licenses:
---------------------------------------
The bitaddress.org project, AI Power Grid (AIPG) and Telestai software and embedded resources are
copyright bitaddress.org.

The Telestai  name and logo are not part of the open source
license.

Portions of the all-in-one HTML document contain JavaScript codes that
are the copyrights of others. The individual copyrights are included
throughout the document along with their licenses. Included JavaScript
libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:

JavaScript function	|	License
-------------------	|	--------------
Array.prototype.map	|	Public Domain
window.Crypto | BSD License
window.SecureRandom	| BSD License
window.EllipticCurve	|	BSD License
window.BigInteger |	BSD License
window.QRCode | MIT License
window.Bitcoin | MIT License

Telestai  - Paper Wallet software is available under The MIT License (MIT)
Copyright (c) 2024 telestai.io

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
