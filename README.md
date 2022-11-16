# Token Descriptions for 3xcalibur

If you're a protocol looking to add your token's description, fork this repo and update as follows:

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
