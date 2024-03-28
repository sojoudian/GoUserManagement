# GoUserManagement

install the following packages:

```bash
go get "github.com/lib/pq"
go get "golang.org/x/crypto/bcrypt"
```

## How to register a new user
```bash
 curl -X POST -d "username=batman&password=1234" http://localhost:8044/register
 ```
 ## How to login with the  registered user:
```bash
curl -X POST -d "username=maziar&password=1234" http://localhost:8044/login
```