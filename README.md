# Tutorial: Developing a RESTful API with Go and Gin

- https://go.dev/doc/tutorial/web-service-gin#all_items
- use `go get .` to add the github.com/gin-gonic/gin module as a dependency for your module. Use a dot argument to mean “get dependencies for code in the current directory.”
- run code in the current directory: `go run .`.
- use curl to make a request to your running web service: `curl http://localhost:8080/albums`.

```
curl http://localhost:8080/albums \
    --include \
    --header "Content-Type: application/json" \
    --request "POST" \
    --data '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```
