# Bitcoin Miner

Project to see how SHA256 and Bitcoin mining work under the hood.


1) Identify the main components, such as the function for importing block data,extracting
   necessary information for mining, and interacting with the external miner.
2) Test each component of your program thoroughly to ensure correctness. Verify that the imported block data is accurate, the mining process functions as expected, and the interactions with the external miner are successful.
3) Implement the continuous monitoring functionality by periodically pinging the local Bitcoin node for the block updates.  Whenever a new block is detected, re –run the mining function with the latest block data.

## Features

- SHA256 implemented from scratch
- Mines block given difficulty in bits format
- Displays current hashrate

SHA256 description: https://eips.ethereum.org/assets/eip-2680/sha256-384-512.pdf
