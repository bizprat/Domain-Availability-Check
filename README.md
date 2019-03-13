# Description

This Node.JS code checks whether the domain is avaialble to buy or not.

# How to use?

1. Download the code
2. Run `npm install` command to install all the dependencies
3. Create new file with name **domains.txt** and list all the domains to be checked. Add one domain per line and make sure it does not containe http, www or any other thing with it.
4. After the setup has been done, run `npm start` command to start the script.
5. The script will filter out the domains and create 2 separate files as follow:
    1. **available.txt** - This file contains the domain names which are available to be registered.
    2. **error-checking.txt** - This file contains the domain names which couldn't be checked now and have to re-check later.

# Developer & Credits

- [Prateek Anand](https://www.facebook.com/prateek707)
- [Chalk](https://github.com/chalk/chalk)
- [whois](https://github.com/hjr265/node-whois)