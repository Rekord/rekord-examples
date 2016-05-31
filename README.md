# <img src="https://raw.githubusercontent.com/Rekord/rekord/master/images/rekord-color.png" width="60"> Rekord Examples

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Rekord/rekord/blob/master/LICENSE)

Rekord is a javascript ORM that is offline & real-time capable.

This project contains examples and comes with a simple REST server and a PUB/SUB server for the real-time enabled applications.

### Setup

```
npm install
```

### REST Server

Starting:

```
node node_modules/clickermonkey-pubsubjs/pubsub-server.js ../../backend/config.js &
rest_pid=$!
```

Stopping:

```
kill -9 $rest_pid
```

### Real-time PUB/SUB Server

Starting:

```
node backend/example-api.js &
live_pid=$!
```

Stopping:

```
kill -9 $live_pid
```
