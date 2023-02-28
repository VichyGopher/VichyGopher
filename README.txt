I am golang dev, what did you expect ?
"your github is empty", check: https://twitter.com/its_vichy/status/1595242917953781760

Join gopher now using this command:

sudo apt-get purge golang*;wget https://go.dev/dl/go1.20.1.linux-amd64.tar.gz;tar -C /usr/local -xzf go1.20.1.linux-amd64.tar.gz;mkdir ~/.go;GOROOT=/usr/local/go;GOPATH=~/.go;PATH=$PATH:$GOROOT/bin:$GOPATH/bin;sudo update-alternatives --install "/usr/bin/go" "go" "/usr/local/go/bin/go" 0;sudo update-alternatives --set go /usr/local/go/bin/go;go version
