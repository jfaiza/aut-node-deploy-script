# aut-node-deploy-script
Script to deploy an autonity node

To execute the script:
 - STEP 1 : Execute the script :
            $ sudo bash "script file"

IMPORTANT: Ref: https://docs.autonity.org/node-operators/install-aut/
You need to add the following ports:

  "A public-facing internet connection with static IP is required. Incoming traffic must be allowed on the following:
    TCP, UDP 30303 for node p2p (DEVp2p) communication.
  You may also choose to allow traffic on the following ports:
    TCP 8545 to make http RPC connections to the node.
    TCP 8546 to make WebSocket RPC connections to the node.
    TCP 6060 to export Autonity metrics (recommended but not required)"
