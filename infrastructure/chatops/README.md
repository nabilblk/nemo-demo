```

 cat secret-discord-kyc.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-discord-kyc.yaml

```


```

 cat secret-discord-blockchain.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-discord-blockchain.yaml

```