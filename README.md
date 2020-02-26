# meeshkan-hosted-secrets
Utility python package to access [Secret Manager](https://cloud.google.com/secret-manager/docs) secrets on [meeshkan.io](https://meeshkan.io).

```python
from meeshkan_hosted_secrets import access_secret_string

secret_value = access_secret_string("MY_SECRET_NAME")
```
