![Travis](https://travis-ci.org/sipcapture/captagent.svg?branch=master)

![](http://i.imgur.com/3kEIR.png)

CaptAgent 6 Project
=========

#####The Next-Generation capture agent for Sipcapture's [Homer](https://github.com/sipcapture/homer) Project
-------------

Download the latest code from our repository and compile it on your system.

Capagent requires: *libexpat, libpcap, libtool, automake* to compile.
```
  cd /usr/src
  git clone -b captagent6 https://github.com/sipcapture/captagent.git captagent
  cd captagent
  ./build.sh
  ./configure
  make && make install
```
  
#### IMPORTANT: 
If you want to enable SSL transport or Payload-Compression use the following flags *(req: libssl-dev, openssl-devel )*:

```
  ./configure --enable-ssl --enable-compression
  make && make install
```

Captagent should be now ready to be configured.

## Configuration

Captagent 6 provides a modular configuration structure supporting includes.
To get familiar with the new configuration please see https://github.com/sipcapture/captagent/tree/master/conf


-------------

### Support
If you found a bug or issue with the code, please raise an Issue on the project tracker.

If you have specific questions or require professional support please contact us at support@sipcapture.org

![HomerFlow](http://i.imgur.com/U7UBI.png)


### Developers
Contributions to our project are always welcome! If you intend to participate and help us improve CAPTANGENT, we kindly ask you to sign a [CLA (Contributor License Agreement)](http://cla.qxip.net) and coordinate at best with the existing team via the [homer-dev](http://groups.google.com/group/homer-dev) mailing list.


----------

##### If you use CAPTAGENT in production, please consider supporting us with a [donation](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=donation%40sipcapture%2eorg&lc=US&item_name=SIPCAPTURE&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=donation%40sipcapture%2eorg&lc=US&item_name=SIPCAPTURE&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHostedGuest)


