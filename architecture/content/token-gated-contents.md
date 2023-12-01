# Token-gated contents

Encrypted text can be embedded into content too, the community doesn’t care what is inside the content, so the most important thing is the encryption service, the Lit Protocol.

Most cases in Lit Protocol are on Ethereum, but for NEAR we build a customized condition code for drips checking.

```jsx
isCreator: "ipfs://QmUzSXwgpB3BC4r73f1GKwQgpV7FXov5SeswCVoSQ9HJ97",
holdTokenGated: "ipfs://QmT3svDg7Y8MKq51kjoiFB8CDe75jzCXV1CkxSYhyxLe4L",
burnTokenGated: "ipfs://QmYtPQTrebRyZRuNuLkw2HyS6AwA72qXDWeWG2oQggbQ59",
signAccess: "ipfs://QmaFrkH8rjPGFBhXSKvY4R6F5dMeCwxMD5dJJsabrqFvp5", //for token-gated community 
```

The encryption part looks like this:

<figure><img src="../../.gitbook/assets/Untitled 2.png" alt=""><figcaption></figcaption></figure>

Lit nodes only hold hashed conditions and encrypted keys in the end and turn them to lot of shares.

The decryption part looks like this:

<figure><img src="../../.gitbook/assets/Untitled 3 (1).png" alt=""><figcaption></figcaption></figure>

As Lit nodes only hold encrypted keys and conditions, those things can be an ID to infer which key should be found in nodes.

The key can be delivered to the user after the condition is fulfilled in the figure.
