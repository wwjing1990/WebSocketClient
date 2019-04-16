# WebSocketClient

A lightweight websocket client implemented in c++, based on libcurl(introduced for HTTP implementation).

## Usage

Just copy files under src/ into your project, and add curl include directory, link libcurl library.  
Note: also link Ws2_32.lib on Windows.

## Dependencies

- [libcurl](https://curl.haxx.se) (required) [download releases](https://curl.haxx.se/download.html)
- [openssl](https://www.openssl.org) (optional, depending on your curl library) [Windows releases](https://curl.haxx.se/windows/)
