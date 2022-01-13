<a id="src.td.auth"></a>

# src.td.auth

[[view_source]](https://github.com/thedemons/desktop-tutorial/blob/4995d67e88268ff635fe9d7620c9d89cafe549a5/src\td\auth.py#L1)

<a id="src.td.auth.AuthKey"></a>

## AuthKey Objects

```python
class AuthKey(BaseObject)
```

[[view_source]](https://github.com/thedemons/desktop-tutorial/blob/4995d67e88268ff635fe9d7620c9d89cafe549a5/src\td\auth.py#L10)

Authorization key

**Attributes**:

- `DcId` _DcId_ - Data Center ID (from 1 to 5)
- `type` _AuthKey.Type_ - Type of the key
- `key` _bytes_ - The actual key, 256 bytes in length
