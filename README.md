### About
Project that tries to use [js-libp2p-webrtc-direct](https://github.com/libp2p/js-libp2p-webrtc-direct) for IPFS node.
- `node node-ipfs.js` to run an IPFS node by nodejs.
- Copy-paste the address from `Swarm listening on <address to copy-paste>` into the field `list` in `public/browser-ipfs.js`:
  ```js
      peerDiscovery: {
        [Bootstrap.tag]: {
          enabled: true,
          list: ['<paste the address here>']
        }
      }
  ```
- `npm run dev` to run the browser version
- open ` http://127.0.0.1:12345` to see the browser version
