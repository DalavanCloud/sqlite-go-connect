# sqlite-go-connect

Simple go app to load the SQLite file (`movies.db`) included in this repo.

## Installation

1. Install go (tested with v1.11) and set $GOPATH
2. Install dep (tested with v0.5.0)
3. Run `dep ensure` to install dependencies

## Running

1. Run `go run main.go` to run the app
2. Make sure you see output like this
```
------------------------------------
Title: Memento
Director: Christopher Nolan
Year: 2000
Runtime: 113
------------------------------------
Title: Raiders of the Lost Ark
Director: Steven Spielberg
Year: 1981
Runtime: 115
------------------------------------
Title: Gran Torino
Director: Clint Eastwood
Year: 2008
Runtime: 116
------------------------------------
...
```

## Preparing for the onsite

We want you to feel prepared for the on-site. Before you arrive, be able to answer the following questions using the dataset we've provided:

1. What is the longest-running movie?
2. What movie has the most actors?
3. What is the breakdown of top movies by rating?
