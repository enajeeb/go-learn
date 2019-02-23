# Learn Go

## Installation
[macOS package installer](https://golang.org/doc/install#macos)

Add path to ~/.bash_profile
```
export PATH=$PATH:/usr/local/go/bin
```

## Go Commands

[Command go](https://golang.org/cmd/go/)

| Command | Details  |
|---|---|
| go build file.go | Compile binary |
| go clean -i | Clean archive and binary |
| go run hello.go | Compile and run |

## Architecture Apps
```
From Mac:
go build -o test . 
For Linux
GOOS=linux GOARCH=amd64 go build -o test-linux . 
For windows:
GOOS=windows GOARCH=386 go  build -o test-windows .
```

## References
* [Go Tour](https://tour.golang.org/list)
* [Effective Go](https://golang.org/doc/effective_go.html)
* [Modern Golang Programming](https://www.safaribooksonline.com/videos/modern-golang-programming/9781787125254/9781787125254-video1_2?autoplay=false)
* [Go (Golang) GOOS and GOARCH](https://gist.github.com/asukakenji/f15ba7e588ac42795f421b48b8aede63)