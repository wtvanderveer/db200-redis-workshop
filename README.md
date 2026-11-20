# DB200 Redis Workshop

A walkthrough of basic Redis commands: strings (`GET`/`SET`), counters (`INCR`), expiring keys (`EXPIRE`/`TTL`), lists, and sets.

## Running the tests

1. Start Redis on `localhost:6379`. On Windows, Redis runs in WSL and stops when no WSL window is open, so keep one open.
2. Run the walkthrough commands against Redis.
3. Install dependencies and run the tests:

```sh
npm install
npm test
```

The tests check that Redis holds the expected final state from the walkthrough.
