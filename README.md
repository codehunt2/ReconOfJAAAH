[ BUG - HUNTERS ] Automated reccon script tool. [ BUG-BOUNTY ]

To use go must be installed.

It is not installed uncomment the dependent lines at the beginning of the code to download the scripts.

The code can be changed to the wordlist to make recons of subdomains, adding your directory.

#install dependency
[x] goland - https://golang.org/doc/install
[x] GO111MODULE=on go get -v github.com/projectdiscovery/subfinder/cmd/subfinder
[x] go get -u github.com/tomnomnom/assetfinder
[x] go get -u github.com/tomnomnom/hacks/ettu
[x] GO111MODULE=on go get -v github.com/projectdiscovery/naabu/cmd/naabu
[x] go get -u github.com/tomnomnom/httprobe
[x] go get github.com/tomnomnom/waybackurls
[x] GO111MODULE=on go get -u -v github.com/projectdiscovery/nuclei/cmd/nuclei
[x] git clone https://github.com/projectdiscovery/nuclei-templates.git


![giphy](https://user-images.githubusercontent.com/28729614/85300599-c571d880-b474-11ea-9eb1-38f4e82c8bae.gif)