# Local TLD
[![Build Status](https://travis-ci.org/hoodiehq/local-tld-lib.svg)](https://travis-ci.org/hoodiehq/local-tld-lib)

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
