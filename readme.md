# Token Lists


This list contains a lists of token metadata (e.g. address, decimals, ...) used by DeSwap interface for fetching and displaying tokens. 

This list only contains tokens for CubeChain (mainnet and testnet)

## How to add new tokens

To add your token to tokens.json, simply copy and paste the JSON object at the end of the list and replace the info with your correct token metadata.

If you have the token logo hosted somewhere, replace the logoURI with a link to the png file. If not, add your logo to the images folder in this format

`
                [address].png
`

logoURI will then be "https://raw.githubusercontent.com/DeSpaceDeFi/tokenLists/cubeChain/images/[address].png"

```json
    {
        "name": "WCUBE Token",
        "symbol": "WCUBE",
        "address": "0x9D3F61338d6Eb394e378D28C1Fd17d5909aC6591",
        "chainId": 1818,
        "decimals": 18,
        "logoURI": "https://raw.githubusercontent.com/DeSpaceDeFi/tokenLists/cubeChain/images/0x9D3F61338d6Eb394e378D28C1Fd17d5909aC6591.png"
    },
```

Please not that "address" be checkSummed address 