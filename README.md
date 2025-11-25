Installation of Go-based tools.

First install golang-go by command sudo apt install golang-go
If already installed then check it by using command go version, if it shows the version then it is installed.

1) installation of subfinder(subdomain discovery tool)
  command:- go install github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
  Use -v if you want to see detailed output.

3) Installation of Assetfinder
   Commmand:- go install github.com/tomnomnom/assetfinder@latest

4) Installation of AlterX
   Command:- go install github.com/projectdiscovery/alterX/cmd/alterx@latest
   
5) Installation of HTTPx (https/http endpoints)
   go install github.com/projectdiscovery/httpx/cmd/httpx@latest

6) Installation of GAU(GetAllURLs)
   Command:- go install github.com/lc/gau/v2/cmd/gau@latest
   
7) Installation of Fuzzuli
   Command:- go install github.com/musana/fuzzuli@latest

8) Installation of Waybackurls
   Command:- go install github.com/tomnomnom/waybackurls@latest

For cross check, enter command (ls ~/go/bin) you will see all the go-based tools we have installed, if not then reinstall it.


   
