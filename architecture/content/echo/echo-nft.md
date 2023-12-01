# Echo NFT

For now, we support Ethereum NFTs to be embedded. Depending on the echo rule we mentioned above, those EVM addresses should be awarded with drips too. Then we represent abstract accounts in community contracts.

The procedure is the same with echo, but the only difference is that A is an EVM address, we can see the difference from the figure:

<figure><img src="../../../.gitbook/assets/Untitled 5.png" alt=""><figcaption></figcaption></figure>

The account system in the community contract can be seen as a key-map store, the key is not only for Near accounts but also anything. Based on that, the community can prove drips that the EVM address was indeed earned.

Then if the EVM address owner comes to Popula, he can check whether he has drips under his address, and gather those drips into his Near account just after a two-way proof that the EVM address signs a message includes Near account name and the Near account calls gather method on community.

Contract Interface Reference:

[https://www.notion.so/beepopula/Community-Interface-Doc-4587da37e8e244408edf51d5caaa82a0](https://www.notion.so/Community-Interface-Doc-4587da37e8e244408edf51d5caaa82a0?pvs=21)
