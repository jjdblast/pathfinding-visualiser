# pathfinding-visualiser

[![Build Status](https://secure.travis-ci.org/Tyriar/pathfinding-visualiser.png)](http://travis-ci.org/Tyriar/pathfinding-visualiser)
[![Code climate](https://codeclimate.com/github/Tyriar/pathfinding-visualiser.png)](https://codeclimate.com/github/Tyriar/pathfinding-visualiser)
[![Dependency Status](https://gemnasium.com/Tyriar/pathfinding-visualiser.svg)](https://gemnasium.com/Tyriar/pathfinding-visualiser)

Visualises pathfinding algorithms.

 - [Demo][1]
 - [Write up][2]

## Setup

```
bower install
npm install -g vulcanize
npm install
```

## Building

```
grunt
```

## Testing

```
npm test
```

## Running locally

Due to browser security features, HTML imports don't work when runnign a page from your filesystem. A simple server can be started on the current directory with Python like so:

```
# Non-Windows
python -m SimpleHTTPServer 8000
# Windows
python -m http.server 8000
```


  [1]: http://www.growingwiththeweb.com/p/html5-demo.html
  [2]: http://www.growingwiththeweb.com/2012/06/a-pathfinding-algorithm.html
