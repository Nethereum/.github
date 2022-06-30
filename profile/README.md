# Nethereum

Nethereum is the Ethereum .Net integration platform, the aim is to provide solutions to develop any type of dapp (web, mobile, desktop), backend integration or gaming and VR using platforms like Unity3d.

## Nethereum Playground. Try Nethereum now in your browser.
The Nethereum playground http://playground.nethereum.com provides a simple IDE with many examples and first point of documentation on common tasks using Nethereum.

[![Nethereum Playground](playground.png)](http://playground.nethereum.com)

## Do you need support, want to have a chat, or want to help?
Please join the Discord server using this link: https://discord.gg/u3Ej2BReNn
We should be able to answer there any simple queries, general comments or requests, everyone is welcome.
If you want to help or have any ideas for a pull request just come and chat.

## Documentation
The documentation and guides can be found at [Read the docs](https://nethereum.readthedocs.io/en/latest/). 

## Examples and Templates
The simplest way to get started, is to use one of the provided examples or templates

### Nethereum.Templates.Pack
The nethereum templates pack includes templates to work and create smart contract libraries, standalone or using a contract framewowrk like Open Zeppelin.
It also includes Blazor wasm and server project templates that integrate with Metamask or Siwe (Sign with Ethereum)

##### Installation
Nuget: https://www.nuget.org/packages/Nethereum.Templates.Pack/

```dotnet new -i Nethereum.Templates.Pack```

##### Templates included

```
Template Name                                                  Short Name           Language  Tags
-------------------------------------------------------------  -------------------  --------  -----------------------------------------------------
Nethereum Default Smart contract Library / XUnit ERC20 sample  smartcontract        [C#]      Nethereum/Smart contracts
Nethereum ERC721, ERC1155 Open Zeppelin and  XUnit Projects    nethereum-erc721-oz  [C#]      Nethereum/Smart contracts/OpenZeppelin/ERC721/ERC1155
Nethereum Blazor Metamask Wasm-Server Projects                 nethereum-mm-blazor  [C#]      Nethereum/Blazor/Metamask
Nethereum Blazor SIWE Wasm/Server/RestApi Projects             nethereum-siwe       [C#]      Nethereum/SIWE/Blazor/Metamas/RestApi
Nethereum WebSocket Streaming Examples                         nethereum-ws-stream  [C#]      Nethereum/WebSocketStreaming
```
##### Nethereum Default Smart contract Library / XUnit ERC20 sample

##### Nethereum ERC721, ERC1155 Open Zeppelin and  XUnit Projects 

##### Nethereum Blazor Metamask Wasm-Server Projects

##### Nethereum Blazor SIWE Wasm/Server/RestApi Projects

### Wallets and End to End examples


### Unity 3D projects templates
#### Getting started (Unity3d Net472 Sample)
Source: https://github.com/Nethereum/Unity3dSimpleSampleNet472

* How to make a simple call to Ethereum (BlockNumber) using Unity.UI both in Async and coroutines
* Ether transfer using Unity.UI and coroutines
* Using 1559 Suggestion strategies or Legacy mode when tranfering Ether
* Smart contract deployment (ERC20), Transactions (Transfer) and Querying (Balance)

#### Unity WebGl 
Source: https://github.com/Nethereum/Nethereum.Unity.Webgl

Example on how to integrate a WebGl unity project with Metamask, Deploy an ERC721 smartcontract (NFT) and interact with the smart contract minting a token and retrieving the asset (image) associated with it.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
