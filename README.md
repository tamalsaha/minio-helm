# minio-helm

- https://github.com/appscode/third-party-tools/tree/master/storage/minio


## Longhosrn

- https://longhorn.io/docs/1.3.1/snapshots-and-backups/backup-and-restore/set-backup-target/#set-up-a-local-testing-backupstore
- https://raw.githubusercontent.com/longhorn/longhorn/v1.3.1/deploy/backupstores/minio-backupstore.yaml

## bitnami

- https://artifacthub.io/packages/helm/bitnami/minio

```
> k port-forward svc/minio :9001
> k view-secret minio --all
```

## 

```
  Access Key: longhorn-test-access-key
  Secret Key: longhorn-test-secret-key
  Default Region: us-east-1
  S3 Endpoint: localhost:9000
  DNS-style bucket+hostname:port template for accessing a bucket: localhost:9000
  Encryption password:
  Path to GPG program: /opt/homebrew/bin/gpg
  Use HTTPS protocol: True
  HTTP Proxy server name:
  HTTP Proxy server port: 0


$ s3cmd ls --no-check-certificate
2022-12-30 16:57  s3://backupbucket
```
