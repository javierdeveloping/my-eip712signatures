## EIP-712 Signatures

EIP-712 introduced the ability to sign transactions off-chain which other users can later execute on-chain. A common example is EIP-2612 gasless token approvals.

Traditionally, setting a user or contract allowance to transfer ERC-20 tokens from an owner’s balance required the owner to submit an approval on-chain. As this proved to be poor UX, DAI introduced ERC-20 permit (later standardized as EIP-2612) allowing the owner to sign the approval off-chain which the spender (or anyone else!) can submit on-chain prior to the transferFrom.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```
$ forge build
```

### Test

```
$ forge test
```
