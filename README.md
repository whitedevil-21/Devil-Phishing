Disclaimer

Any actions and or activities related to Zphisher is solely your responsibility. The misuse of this toolkit can result in criminal charges brought against the persons in question. The contributors will not be held responsible in the event any criminal charges be brought against any individuals misusing this toolkit to break the law.

This toolkit contains materials that can be potentially damaging or dangerous for social media. Refer to the laws in your province/country before accessing, using,or in any other way utilizing this in a wrong way.

This Tool is made for educational purposes only. Do not attempt to violate the law with anything contained here. If this is your intention, then Get the hell out of here!

It only demonstrates "how phishing works". You shall not misuse the information to gain unauthorized access to someones social media. However you may try out this at your own risk.

Features
Latest and updated login pages.
Beginners friendly
Multiple tunneling options
Localhost
Cloudflared
LocalXpose
Mask URL support
Docker support
Installation
Just, Clone this repository -

git clone --depth=1 https://github.com/htr-tech/zphisher.git
Now go to cloned directory and run zphisher.sh -

$ cd zphisher
$ bash zphisher.sh
On first launch, It'll install the dependencies and that's it. Zphisher is installed.

Installation (Termux)
You can easily install zphisher in Termux by using tur-repo

$ pkg install tur-repo
$ pkg install zphisher
$ zphisher
A Note :
Termux discourages hacking .. So never discuss anything related to zphisher in any of the termux discussion groups. For more check : wiki



Installation via ".deb" file
Download .deb files from the Latest Release

If you are using termux then download the *_termux.deb

Install the .deb file by executing

apt install <your path to deb file>
Or

$ dpkg -i <your path to deb file>
$ apt install -f
Run on Docker
Docker Image Mirror:

DockerHub :
docker pull htrtech/zphisher
GHCR :
docker pull ghcr.io/htr-tech/zphisher:latest
By using the wrapper script run-docker.sh

$ curl -LO https://raw.githubusercontent.com/htr-tech/zphisher/master/run-docker.sh
$ bash run-docker.sh
Temporary Container

docker run --rm -ti htrtech/zphisher
Remember to mount the auth directory.
