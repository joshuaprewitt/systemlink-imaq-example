# systemlink-imaq-example
 
This example demonstrates how to trigger an image acquisition from an IC-3173 using a SystemLink message and then publish the image as a tag that can then be viewed from the SystemLink Server web interface.

Includes a package for deploying the LV RT applicaiton to the target and a package for installing the WebVI to the SystemLink Server. Note, you may need to open the NI Web Server Configuration utility on the server and restart the web server before the IMAQ Example application will show up in SystemLink.

For more information on how to get your WebVI to show up as a SystemLink application see - https://github.com/ni/systemlink-web-interface-template

Requires LabVIEW 2019 and NXG 5.0 Web Module

![alt LabVIEW and NXG](https://github.com/joshuaprewitt/systemlink-imaq-example/blob/master/lv-nxg-imaq.png)

![alt SystemLink](https://github.com/joshuaprewitt/systemlink-imaq-example/blob/master/sl-imaq.png)
