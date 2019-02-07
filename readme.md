# Agent API

Holds a mock of the controls an agent provides.

Will try to extract all triples in the folder and expose them as JSON-LD

Usage:

```
npm install
npm start
```

then go to http://localhost:3000

The data is in`/mock` directory, modify and refresh to see how it goes.

you can use the placeholders {{base}} or {{current}} they will be replaced by the base URL and the current request URL respectively.

## Relevant dependencies. 

Joachim's 

https://github.com/joachimvh/n3-parser.js

Ruben's 
Lightning fast N3 https://github.com/rdfjs/N3.js