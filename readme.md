# Requirements
- Truffle version: Truffle v5.1.14-nodeLTS.0
- OpenZeppelin version: 2.1.2
# Token info of the Contract
- ERC-721 Token Name (Starname): MyStarNotary Pertek
- ERC-721 Token Symbol (Starsymbol): MSN
- “Token Address” on the Rinkeby Network: 0xB507343753E71D6251665Ae226B37e3b9aC03a35

# Run the app
## Start WebServer
- cd app
- npm run dev

## Start Truffle (in new terminal)
- truffle develop

## Browse the app in a webbrowser (likely Chrome)
URL http://localhost:8081/

## Trouble shooting
if an error "gas limit" is displayed in metamask when doing an transaction then
- in truffle call migrate --reset
- maybe change network in metmask to other network and then back to "truffle port 9545"

if error "payload" is displayed in metamask when doing an transaction then use the function "reset account" in metamask

# Develop (change contract code)
- truffle develop
- compile
- migrate --reset --network rinkeby