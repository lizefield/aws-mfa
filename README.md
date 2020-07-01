# aws-mfa

## 設定

1. Pathの通ったところに `aws-mfa` を配置  
2. `aws-mfa` の `AWS_MFA_DEVICE_ARN` に自分のMFA Serialを記述  
3. `chmod +x aws-mfa` で実行権限を付与  

## 使い方

```
$ aws-mfa  
Input MFA Code: <input code>  
```

