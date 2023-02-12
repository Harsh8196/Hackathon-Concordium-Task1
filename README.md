# Hackathon-Concordium-Task1

## Installing Rust
I downloaded Rustup from https://win.rustup.rs/x86_64 and ran the installer:
![image](https://user-images.githubusercontent.com/35626990/218310948-faf2cbd2-c657-42bc-acdc-2fe4b63feef6.png)

## Installing Wasm
* Executed command:- ** rustup target add wasm32-unknown-unknown **
![image](https://user-images.githubusercontent.com/35626990/218311141-7d4b7385-8e23-439f-9485-05b2e70563cc.png)

## Installing cargo-concordium
* I downloaded cargo-concordium from https://developer.concordium.software/en/mainnet/net/installation/downloads-testnet.html#cargo-concordium-testnet
* Renamed the cargo-concordium-v.x.x file to cargo-concordium.
* Moved the executable to a folder %HOMEPATH%\.cargo\bin\ for Windows.
* Executed command ** cargo concordium --help **
![image](https://user-images.githubusercontent.com/35626990/218311482-604300a1-d402-40a6-b033-9f41525b2eb2.png)

## Installing Concordium Client
* I downloaded cargo-concordium from https://developer.concordium.software/en/mainnet/net/installation/downloads-testnet.html#concordium-node-and-client-download-testnet
* Renamed the package to ** concordium-client **
* Go to the folder where you downloaded the concordium-client and executed command ** concordium-client --help **
![image](https://user-images.githubusercontent.com/35626990/218311710-dc11dd67-dabc-49e2-a805-e485a9f00838.png)

* Executed command to connect with public test node ** concordium-client consensus status --grpc-port 10000 --grpc-ip node.testnet.concordium.com **
![image](https://user-images.githubusercontent.com/35626990/218311793-2abcb0f0-7949-4173-8161-ba65d00ee703.png)

## Setup a wallet
* I downloaded Concordium Wallet for Web from https://chrome.google.com/webstore/detail/concordium-wallet/mnnkpffndmickbiakofclnpoiajlegmg?hl=en-US
* Installed and setup wallet 
![image](https://user-images.githubusercontent.com/35626990/218311900-0f2ffa06-0c8a-4e7c-b01b-47df0a49956c.png)

## Export the key
![image](https://user-images.githubusercontent.com/35626990/218311949-d12dcf3c-813b-48a4-87af-1007e865e101.png)
![image](https://user-images.githubusercontent.com/35626990/218312018-74762cb9-c3c0-4f3c-8eba-4937c2394b58.png)

## Import the key
* Executed command ** concordium-client config account import 3FDi9U6CWMkVeYdw5UYtDGU8Rd1UJrZXwVTJ4ayxyQQwT7muS6.export --name HarshM **
![image](https://user-images.githubusercontent.com/35626990/218312128-aa419863-2b04-46bf-82ef-382fdf55ade2.png)

# Mainnet Account:



