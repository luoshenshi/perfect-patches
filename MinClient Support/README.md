## MinClient Support

**MinClient Support** is a feature/fix patch that introduces a custom-made HTTPS client.

It works similarly to **OkHttp**, but is intentionally **very minimal**. This client is used to support other patches, as the app is based on the old-school **`HttpsURLConnection`** (Java) networking approach for making requests.
