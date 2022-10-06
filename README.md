# s3-sync-action

This action syncs the provided S3 bucket with the contents of the provided path

## Inputs
```yaml
bucket-name:
    required: true
    description: Desired Bucket Name
bucket-expiration:
    required: false
    default: '30'
    description: Desired Bucket Expiration Time in Days
bucket-region:
    required: false
    default: 'us-east-2'
    description: Desired Bucket AWS Region
bucket-path:
    required: false
    default: '/'
    description: Relative Upload Path
aws-access-key-id:
    required: true
    description: AWS Access Key ID
aws-secret-access-key:
    required: true
    description: AWS Secret Access Key
content-path:
    required: true
    description: Path of the Content to Sync
```
