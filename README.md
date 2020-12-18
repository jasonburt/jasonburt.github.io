# Kat's Awesome Blog
From
https://github.com/jasonburt/kats_awesome_blog

If you're looking for a way to quickly and easily get up and running with a Blog this is the project for you.

This project is a [Github Pages Blog](https://pages.github.com/)  with the following services:

None

Pages is a free service to remotely manage and update your Blog through an online dashboard interface, as well as providing remote access to the Pi-hole web interface without any additional configuation.

## Getting Started

To get started you'll first need to sign up for a free balenaCloud account and flash your device.

<https://guides.github.com/activities/hello-world/>

## Deployment

Once your account is set up, deployment is carried out by downloading the project and pushing it to GitHub with Git.


### ENV Variables

There are no ENV Variables for this, but if you want you can set some up...

|Service|Name|Example|Purpose|
|---|---|---|---|
|`pihole`|`DNSMASQ_LISTENING`|`eth0`|We set this to `eth0` to indicate we want DNSMASQ to listen on the ethernet interface of the Raspberry Pi. If you're connecting to your network with WiFi replace this with `wlan0`|

## Usage

* <https://pages.github.com/>

Note that you can change the project by editing the html file.

## Help

If you're having trouble getting the project running, submit an issue to github or tweet at [Kat](https://twitter.com/Dixie3Flatline).

## Author

Jason Burt <nadaanaddress@gmail.com>

## Acknowledgments

* <https://github.com/pi-hole/docker-pi-hole/>
* <https://github.com/jedisct1/dnscrypt-proxy>
* <https://firebog.net/>

## License

[MIT License](./LICENSE)
