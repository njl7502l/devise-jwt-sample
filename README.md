# README


railsサーバを立てつつ `curl -D - -o /dev/null http://localhost:3000/users/sign_in -H 'content-type: application/json' -d '{"user": {"email": "test@example.com", "password": "password"}}' `で閲覧できる

