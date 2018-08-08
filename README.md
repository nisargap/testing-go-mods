## Testing Go Modules

**Setting Up**

- Set $GOPATH to some other directory than this one

- In that other directory you want to get vgo `go get -u golang.org/x/vgo`

- Alias vgo in your `~/.bashrc` such that `alias vgo="$GOPATH/bin/vgo"`

- Run `source ~/.bashrc` so that `vgo` is available everywhere

- Clone this repo somewhere other than your $GOPATH 

- `cd testing-go-mods` 

- `vgo build` 

- `./main` 


