## 📟 Extended-NEC-decoder
### Convert Extended NEC to Raw NEC data effortlessly!
You can use the converter online at the [link here](https://pm0d.github.io/Extended-NEC-decoder/Extended%20NEC%20decoder.html). 

### Project Background
Have a phone with IR blaster but the remote app doesn't have all the buttons to control your TV or other appliances?  
That's what happened for me, and it sent me down the deep rabbit hole of infrared signal protocols and their various formats.

After a lot of search and research, I finally stumbled upon the missing codes for my appliance on [Lucaslhm's Flipper-IRDB project](https://github.com/Lucaslhm/Flipper-IRDB).   
However, they were in the Extended NEC format, while my remote app required Raw NEC.

Unable to find an online converter, I decided to create one myself. The logic is based on code from the [IRremote ESP8266 Library](https://github.com/r-map/rmap/tree/master/platformio/libraries/IRremoteESP8266).   
Last but not the least, I had a lot of help from Microsoft Copilot and OpenAI ChatGPT for the implementation of the logic and coding.

More on the NEC protocol on this [old site.](https://web.archive.org/web/100/http://www.sbprojects.com/knowledge/ir/nec.php)

If you find it helpful or interesting, star the repo and I will be pleased as punch.
