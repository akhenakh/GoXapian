# GoXapian

## Build on OSX

```
brew install xapian
CGO_LDFLAGS=`pkg-config --libs xapian-core` CGO_CXXFLAGS="`pkg-config --cflags xapian-core` -std=c++11"  go build
```
