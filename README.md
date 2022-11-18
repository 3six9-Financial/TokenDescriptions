# Token Descriptions for 3xcalibur

If you're a protocol and you need to add your token and its description to 3xcalibur, fork this repo and update as follows:

- [Token Entry](token-entry)
- [Token Description](token-description)

## Token Entry

1. Fork the repo by clicking the "fork" button:

![image](https://user-images.githubusercontent.com/97149702/202253268-e39388fe-aba2-4343-a83b-edcd453ad67a.png)

2. Add an entry to `tokenList.json` with the following format:
```
{
  "name": "<the longform name of your token>",
  "symbol": "<what will render in the UI for pairs>",
  "decimals": 18,
  "address": "<your token address>",
  "chainId": 42161,
  "logoURI": "<URL of your token logo>",
},
```

Example:
```
{
  "name": "3xcalibur Ecosystem Token",
  "symbol": "XCAL",
  "decimals": 18,
  "address": "0xaa7bD1B6d7FD6bcF1868B327EE5bDd8349581882",
  "chainId": 42161,
  "logoURI": "https://app.3xcalibur.com/images/XCAL.png",
},
```

3. Open a pull request by clicking "Pull Requests" selecting "New pull request".

4 Make sure to write a description of what protocol, chain, and token in the description, and our team will merge if all is well.

## Token Description

1. Fork the repo by clicking the "fork" button:

![image](https://user-images.githubusercontent.com/97149702/202253268-e39388fe-aba2-4343-a83b-edcd453ad67a.png)

2. Create a description for your token in a json file in the format:
```
{
"<ISO 639-1 2 letter language code, ex>": "<your token's description>"
}
```

Example:
```
{
"en": "XCAL is the 3xcalibur Ecosystem Token."
}
```

3. Save this file with the filename in the format:
```
<token address>.json
```

Example
```
0xd2568accd10a4c98e87c44e9920360031ad89fcb.json <- XCAL token address on Arbitrum
```

4. Make sure the file is saved in `chains/42161`.

5. Open a pull request by clicking "Pull Requests" selecting "New pull request".

6. Make sure to write a description of what protocol, chain, and token in the description, and our team will merge if all is well.
