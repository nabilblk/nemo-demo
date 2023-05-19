## Command to seal secrets : 

```
cat secret-registry-sredx.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-sredx.yaml
```

```
cat secret-registry-accelerate.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-accelerate.yaml
```

```
cat secret-registry-mfa.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-mfa.yaml
```

```
cat secret-registry-kyc.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-kyc.yaml

```

```
cat secret-registry-fraude.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-fraude.yaml
```

```
cat secret-registry-blockchain.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-blockchain.yaml

```



```
cat secret-registry-yakeey.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-yakeey.yaml

```

```
cat secret-flux-source.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-flux-source.yaml

```

```
cat secret-flux-source.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-flux-source.yaml
```

```
cat secret-registry-gpt.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-registry-gpt.yaml
```