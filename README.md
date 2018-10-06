<p align="center">
  <img src="https://github.com/DesmondANIMUS/genie/blob/master/genie-header.png">
</p>

# Genie
A smol &amp; simple Go web app project boiler plate generator that takes care of registering CRUD handlers, CORS, safe headers, logging, multi-threading, mongodb connection.

## How to Use
1. go get -u -v github.com/DesmondANIMUS/genie
2. Navigate to your WORKDIR, defaults: <br/>
  a. Windows: `%userprofile%/go/src/github.com/<github_username>/` <br/>
  b. Linux & MacOS: `$HOME/go/src/github.com/<github_username>/` <br/>
3. Make sure that **"go/bin"** folder has been added to environment variable **Path**
4. genie <project_name>
5. Enjoy!

## Mission
- **Minimalistic**: Minimum, yet useful amount of boiler plate code generation.
- **Productivity**: Let developers spend more time writing the code that matters &amp; less time on project setup.
- **Speed**: Code generation should be as fast as possible.

## Features:
1. Generates minimal boiler plate code to get you started.
2. Registers handlers for CRUD operations.
3. Creates global connection with mongodb that can be extended by cloning the global session.
4. Registers CORS on the api.
5. Adds "safe" headers in the application like content time, x-frame-options etc. to try and avoid security issues.
6. Adds gorilla mux for all handlers.
7. Blazing Fast! Works almost instantly!

### Contribution Guidelines :
1. Fork the repo and create your branch from master.
2. Add the changes/fixes! 
3. Make sure your code lints.
4. Issue that pull request (against `development` branch)!

Please follow contribution guidelines to make things easy for everyone. Thanks ^.^
