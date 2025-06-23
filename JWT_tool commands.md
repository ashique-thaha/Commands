## JWT Tool commands:

```
jwt_tool --alg HS256 --payload '{"sub": "1234567890", "name": "John Doe", "iat": 1643723900, "exp": 2147483647}' --secret-key 'your_secret_key_here' 
```

```
python3 jwt_tool.py -M at \
    -t "https://api.example.com/api/v1/user/76bab5dd-9307-ab04-8123-fda81234245" \
    -rh "Authorization: Bearer eyJhbG...<JWT Token>"
```
