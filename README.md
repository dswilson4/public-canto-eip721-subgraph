Based off of https://github.com/wighawag/eip721-subgraph , this repo includes the most up to date compatible version of erc721 abis

# example graphQL query
```
{
  tokens {
    contract
    tokenID
    owner
    tokenURI
  }
}
```


or

```
{
  tokens(orderBy: mintTime) {
    contract
    tokenID
    owner
    tokenURI
    mintTime
  }
  
  tokenContracts {
    id
  }
}
```
# public-canto-eip721-subgraph
