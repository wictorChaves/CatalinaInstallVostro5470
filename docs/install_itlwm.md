# Install WiFi

 - Download [itlwm.kext.zip](/kext/itlwm.kext.zip)
 - To extract
 - Click on "show contents of package"
 
 ![](/docs/image/mostra_conteudo.jpeg)
 
 - Click on "Open With" > "Xcode"
 
 ![](/docs/image/abri_com.jpeg)
 
 - So edit with your SSID and Password
 
  ![](/docs/image/ssid_senha.jpeg)
  
 - Open the terminal in the kext package folder and run the command below as root
 
 ``` sh
    chown -R root:wheel itlwm.kext
    kextload itlwm.kext
 ```
