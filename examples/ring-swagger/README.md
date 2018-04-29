# WIP: Ring + Swagger example

## Usage

```clj
> lein repl
(start)
```

To test the endpoints using [httpie](https://httpie.org/):

```bash
http GET :3000/api/schema/plus x==1 y==20
http GET :3000/api/spec/plus x==1 y==20

http GET :3000/api/swagger.json
```

* swagger.json: http://localhost:3000/api/swagger.json
* swagger-ui: http://localhost:3000/api-docs/index.html

## License

Copyright © 2017 Metosin Oy
