# P2P Messaging
The project makes use of p2p by implementing peerjs to establish a one to many like message board. It allows for the initiator to create an ID and share it with the peers and can then be connected with the initiator.

## Getting Started

* A stable Internet Connection
* Browser compatible with WebRTC(usually all except IE and Edge)

### Installing

Open your project folder in the terminal

Step 1 : Setting up the environment

```
npm init
npm install npx
npm install peer

```

Step 2 : Set up PeerJS server on port 9000

```
npx peerjs --port 9000
```

Here, I have used port 9000, but you can change it to whatever you set the port in your Peer options.


## Built With

* [PeerJS](https://peerjs.com) - The p2p framework used


## Authors

* **Atharv Sharma** - [Shod0w](https://github.com/Shod0w)

