<img src="https://user-images.githubusercontent.com/1423657/55069501-8348c400-5084-11e9-9931-fefe0f9874a7.png" width=200 /><img src="https://user-images.githubusercontent.com/1423657/96346959-ea7efc80-109e-11eb-861c-23cb61b0c219.png" />

# HEPSUB RTP:Engine 
### Call Recording Endpoint

[HOMER](https://github.com/sipcapture/homer-app) Seven allows external agents to subscribe capabilities to provide *"on-demand"* session details from external APIs, databases, etc. to argument internally available data without requiring data duplication and allowing creative use of the core HEP platform.

This HEPSUB client will receive on-demand request from HOMER sessions, and will attempt locate RTP:Engine metadata and recordings.

```
[ HOMER ] <---> [ HEPSUB-RTPENGINE ] <---> [ RTPENGINE META ]
```

![image](https://user-images.githubusercontent.com/1423657/96891936-6dca9480-1489-11eb-8156-8f85bbfe0eb3.png)



##### Install
```
npm install
```
##### Configure
Configure your HOMER URL, `API Token` and local network settings in file `config.js`

##### Initialize
```
npm start
```

##### Docker
To use our ready container, just populate the following variables and use the included `docker-compose` file:
```
      - PUBLIC_IP=   YOUR SERVICE IP/DOMAIN
      - HOMER_IP=    YOUR HOMER IP
      - HOMER_PORT=  YOUR HOMER PORT
      - HOMER_TOKEN= YOUR HOMER AUTH TOKEN
```

---------

#### Made by Humans
This Open-Source project is made possible by actual Humans without corporate sponsors, angels or patreons.<br>
If you use this software in production, please consider supporting its development with contributions or [donations](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=donation%40sipcapture%2eorg&lc=US&item_name=SIPCAPTURE&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=donation%40sipcapture%2eorg&lc=US&item_name=SIPCAPTURE&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest) 

###### (C) 2008-2020 QXIP BV
