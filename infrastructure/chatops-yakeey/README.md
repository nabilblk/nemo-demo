```

 cat secret-slack-yakeey.yaml | kubeseal \
--controller-namespace sealed-secrets \
--controller-name sealed-secrets \
--format yaml \
> ss-slack-yakeey.yaml

```