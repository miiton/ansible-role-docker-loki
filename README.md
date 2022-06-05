# docker-loki

## Role Variables

```yml
caddy_servername: mycaddy
loki_unuse_iam: true # IAM を使用しないか否か(AWS_ACCESS_KEY などを環境変数として設定する必要がある)
loki_host: loki.example.com
loki_store: gcs # or s3
loki_store_s3_region: ap-northeast-3
loki_store_bucket_name: hogehoge
```
