# Local TLD
[![Build Status](https://travis-ci.org/hoodiehq/local-tld-lib.svg)](https://travis-ci.org/hoodiehq/local-tld-lib)
[![Dependency Status](https://david-dm.org/hoodiehq/local-tld-lib.svg)](https://david-dm.org/hoodiehq/local-tld-lib)
[![devDependency Status](https://david-dm.org/hoodiehq/local-tld-lib/dev-status.svg)](https://david-dm.org/hoodiehq/local-tld-lib#info=devDependencies)

See http://github.com/hoodiehq/local-tld for a description.

## I want my app to register itself with local-tld!

    var ltld = require("local-tld-lib");
    ltld.add("yourfancyproject", 12345);

    // ok cool, how can I deregister?
    ltld.remove("yourfancyproject");

## License

Apache 2 License

## Copyright

(c) 2013 Jan Lehnardt <jan@apache.org>
