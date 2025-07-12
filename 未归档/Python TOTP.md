```python
import pyotp

totp = pyotp.TOTP('')
print(totp.now())
```