.PHONY: build test clean

build:
	cfn generate
	env GOOS=linux go build -ldflags="-s -w" -tags="logging" -o bin/handler cmd/main.go

test:
	rm -f rpdk.log
	cfn generate
	env GOOS=linux go build -ldflags="-s -w" -o bin/handler cmd/main.go
	cfn test

clean:
	rm -rf bin
