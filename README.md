# tabiframe-zimlet
This zimlet is to add a new tab onto Zimbra webmail that loads a complete web page in an iframe. The webpage URL is defined in com_zimbra_tabiframe.js.

To build and install the zimlet:
* Clone the git repository
* Modify tab-url property in config_template.xml to your right webpage
* Modify tab-label property in com_zimbra_tabiframe.properties to your right label
* Run "sh build.sh" to build your zimlet
* Deploy zimlet from the new .zip file
