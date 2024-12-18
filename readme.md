# Json-ld from folder

Reads all the RDF files of a folder and exposes the triples as JSON-LD. 

Useful for quick-mocks

Usage:

```
npm install
npm start
```

then go to http://localhost:3000

The data is in`/mock` directory, modify and refresh to see how it goes.

- If curious, the mock directory contains a mock of the hypermedia controls provided from a personal agent. 

you can use the placeholders {{base}} or {{current}} they will be replaced by the base URL and the current request URL respectively.

## Relevant dependencies. 

Joachim's 

https://github.com/joachimvh/n3-parser.js

Ruben's 
Lightning fast N3 https://github.com/rdfjs/N3.js
