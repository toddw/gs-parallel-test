# gs-parallel-test
Testing out parallel builds in upcoming version of GlueStick

## Setup
```
npm install
```

## Test parallel build then run
```
NODE_ENV=production bin/build
NODE_ENV=production gluestick start -P
```

Open browser to: http://localhost:8880/two
and http://localhost:8880/


