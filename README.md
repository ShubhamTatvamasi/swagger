# swagger

Swagger UI:
```bash
docker run --rm -p 80:80 -p 8080:8080 \
  -e SWAGGER_JSON_URL=https://raw.githubusercontent.com/ShubhamTatvamasi/swagger/master/swagger.yml \
  swaggerapi/swagger-ui
```

Swagger editor: https://editor.swagger.io/
```bash
docker run --rm -p 80:80 -p 8080:8080 swaggerapi/swagger-editor
```
