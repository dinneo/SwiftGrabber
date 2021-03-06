# SwiftGrabber

A automation command line tool that syncs server responses for you.

## Purpose

Client developer should always be offline capable. Less dependency means more freedom! Unfortunately, most of the client development depends on the rest API provided by the server side. 

We may either run a server locally or download the responses to our local machine to address the problem. Run a server locally sounds achievable until we spent two weeks dealing with the environment or spent 10 GB disk space just for the container. A more economical way is to download the responses from the server. 


## Description

The SwiftGrabber is a binary command line tool which downloads a api response from server, and save it to your local file system. It's componsed by Swift Package Manager, and is well modulized for future integration.


## Usage 

```shell
export ACCESS_TOKEN="<http header key>:<your token>"

swiftGrabber -u <URL address> -o <Output path>
```

## Build 

```shell
./build
```