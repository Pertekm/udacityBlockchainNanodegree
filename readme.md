- Truffle version: Truffle v5.1.14-nodeLTS.0
- OpenZeppelin version: 2.1.2
- ERC-721 Token Name (Starname): Wdaw
- ERC-721 Token Symbol (Starsymbol): X
- “Token Address” on the Rinkeby Network: 0x0b4C11be8762e9cA09007499126a7183090aD858

########################################################################


Running app:
- WebServer:
cd app
npm run dev

- Truffle (new terminal):
truffle develop

- Chrome:
http://localhost:8081/
if error "gas limit" when transaction in metamask then
- in truffle call migrate --reset
- maybe change network in metmask to other network and then back to "truffle port 9545"

if error "payload" when transaction in metamask then "reset account" in metamask