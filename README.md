# Google Dorks for Open Storage Buckets
Use with reckless abandon.

# Alicloud

```
site:*.oss-cn-*.aliyuncs.com
inurl:oss-cn-*.aliyuncs.com
"ListObjectsResult" site:.oss-cn-.aliyuncs.com
"Index of" site:.oss-cn-.aliyuncs.com
filetype:xls site:*.oss-cn-*.aliyuncs.com
confidential OR secret OR private site:*.oss-cn-*.aliyuncs.com
intitle:"index of" "last modified" "parent directory" site:*.oss-cn-*.aliyuncs.com
inurl:"/oss-cn-" site:*.aliyuncs.com
```

# AWS
```
site:*.s3.amazonaws.com
inurl:s3.amazonaws.com
"ListBucketResult" site:s3.amazonaws.com
"Index of" site:*.s3.amazonaws.com
"AWS Credentials" site:*.s3.amazonaws.com
filetype:xls site:*.s3.amazonaws.com
filetype:sql site:*.s3.amazonaws.com
confidential OR secret OR private site:*.s3.amazonaws.com
intitle:"index of" "last modified" "parent directory" site:*.s3.amazonaws.com
inurl:"/.aws/credentials" site:*.s3.amazonaws.com
```

# Azure

```
site:*.blob.core.windows.net
inurl:blob.core.windows.net
"ListBlobs" site:blob.core.windows.net
"Index of" site:*.blob.core.windows.net
filetype:xls site:*.blob.core.windows.net
filetype:pdf site:*.blob.core.windows.net
filetype:txt site:*.blob.core.windows.net
confidential OR secret OR private site:*.blob.core.windows.net
intitle:"index of" "last modified" "parent directory" site:*.blob.core.windows.net
inurl:"/azure-webjobs-dashboard/" site:*.blob.core.windows.net
```

# Google
```
site:*.storage.googleapis.com
inurl:storage.googleapis.com
"ListObjectsResponse" site:storage.googleapis.com
"Index of" site:*.storage.googleapis.com
filetype:xls site:*.storage.googleapis.com
confidential OR secret OR private site:*.storage.googleapis.com
intitle:"index of" "last modified" "parent directory" site:*.storage.googleapis.com
inurl:"/storage/browser/" site:*.storage.googleapis.com

```

# Yandex

```
site:*.storage.yandexcloud.net
inurl:storage.yandexcloud.net
"ListObjectsV2Result" site:storage.yandexcloud.net
"Index of" site:*.storage.yandexcloud.net
filetype:xls site:*.storage.yandexcloud.net
filetype:pdf site:*.storage.yandexcloud.net
filetype:csv site:*.storage.yandexcloud.net
confidential OR secret OR private  site:*.storage.yandexcloud.net
intitle:"index of" "last modified" "parent directory" site:*.storage.yandexcloud.net
inurl:"/objects/" site:*.storage.yandexcloud.net
```
