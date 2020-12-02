# dob2hex
An alternative to Yealink's Dob2Text application that you need to request from Yealink reseller or FAE and doesn't really exist on the internet.

## How to use

1. Obtain [PictureExDemo from Archive.org](https://web.archive.org/web/20160810175602/http://www.yealink.com/Upload/document/HowtochangethelogoofYealinkPhonesRev_610/HowtochangethelogoofYealinkPhonesRev_610-20424946725.zip) as it doesn't appear that the tool is available for download anymore from Yealink directly.
2. Look at the `How to change the logo of Yealink Phones` PDF to understand how to use PictureExDemo and the image requirements. Black/White GIFs are ideal for conversion.
3. Run `./dob2hex.sh yourimage.dob`. Script will refuse to run if the `.dob` extension is missing.

Refer to [Yealink SIP IP Phones XML Browser Developer's Guide](http://support.yealink.com/issueSearch?issueId=113) how to utilize the generated hex string with `YealinkIPPhoneImageMenu`.

Tested with Yealink T23G.
