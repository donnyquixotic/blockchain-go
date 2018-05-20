
# Blockchain-Go
This is a simple blochain implementation written in Go allowing broadcasting to multiple nodes

## Getting Started

### Dependencies
Install Go - https://golang.org/doc/install

`go get github.com/davecgh/go-spew/spew` -pretty prints blockchain to console

`go get github.com/joho/godotenv` -load variables in `.env` file

## Deploying blockchain

`go run blockchain.go` -launch blockchain genesis block

## Connecting new client

`nc localhost 9000` -connect to network from a new client (using port # defined by ADDR in .env file)



