amzses
======

This is a Go package to send emails using Amazon's Simple Email Service.

Installation
------------

Use `go get`:

    go get stathat.com/c/amzses

Then

    import (
            "stathat.com/c/amzses"
    )

Using `go get` will automatically install its one external dependency,
[jconfig](http://www.stathat.com/c/jconfig).

Usage
-----

Examples available at [www.stathat.com/c/amzses](http://www.stathat.com/c/amzses).

Status
------

This package was extracted from production code powering [StatHat](http://www.stathat.com),
so clearly we feel that it is production-ready, but it should still be considered
experimental as other uses of it could reveal issues we aren't experiencing.

We only implemented the parts of the API that we are using, so this only sends text emails.

Contact us
----------

We'd love to hear from you if you are using `amzses`!  We're on twitter: [@stathat](http://twitter.com/stathat) or [contact us here](http://www.stathat.com/docs/contact).

About
-----

Written by Patrick Crosby at [StatHat](http://www.stathat.com).  Twitter:  [@stathat](http://twitter.com/stathat)
