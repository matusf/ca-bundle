# CA-bundle

No more `SSLError`s because of unset `REQUESTS_CA_BUNDLE`.

## Usage

```python
import ca_bundle


ca_bundle.install()
```

Inspired by [Go's implementation](https://golang.org/src/crypto/x509/root_linux.go)
