# JSON API TypeScript

Without mongoose:

```
$ npx tsc
node_modules/json-api/build/src/controllers/API.d.ts(2,23): error TS2688: Cannot find type definition file for 'ramda'.
node_modules/json-api/build/src/db-adapters/Mongoose/MongooseAdapter.d.ts(1,23): error TS2688: Cannot find type definition file for 'mongoose'.
node_modules/json-api/build/src/db-adapters/Mongoose/MongooseAdapter.d.ts(2,26): error TS2307: Cannot find module 'mongodb'.
node_modules/json-api/build/src/db-adapters/Mongoose/MongooseAdapter.d.ts(3,27): error TS2307: Cannot find module 'mongoose'.
node_modules/json-api/build/src/db-adapters/Mongoose/MongooseAdapter.d.ts(5,33): error TS2307: Cannot find module 'mongoose'.
```

With mongoose:

```
$ npx tsc
node_modules/json-api/build/src/controllers/API.d.ts(2,23): error TS2688: Cannot find type definition file for 'ramda'.
node_modules/json-api/build/src/db-adapters/Mongoose/MongooseAdapter.d.ts(1,23): error TS2688: Cannot find type definition file for 'mongoose'.
```
