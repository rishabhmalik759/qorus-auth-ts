# Qorus Authentication NodeJS Utility
## Build the project
```
npm run build
```
## Run Tests
```
npm run test
```
## Clean the build directory
``` 
npm run clean
```

## Usage

Install qore-login as a dependencies
```
 npm install --save [https://github.com/rishabhmalik759/qorus-auth-ts](https://github.com/rishabhmalik759/qorus-auth-ts/tarball/master).git
```

The dependency will be added to package.json
```
"dependencies": {
        "qore-login": "git+[https://github.com/rishabhmalik759/qorus-auth-ts.git)"
}
```

Then use the dependency normally
```
import qore from "qore-login"

const qore = require("qore-login")
```

User can login to the auth endpoint using
```
const qoreAuth = new qore();
qoreAuth.login(username, password);
```
