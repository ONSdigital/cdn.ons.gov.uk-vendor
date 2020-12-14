cdn.ons.gov.uk vendored libraries
=================================

Vendored third party CDN libraries for ONS web services.

### Using vendored libraries

The `vendor` directory in this repository is published to the CDN
under an equivalent `vendor` directory.

E.g., to include jQuery 2.1.4 (from [vendor/jquery/2.1.4](vendor/jquery/2.1.4)), you would
link to the file using the following URL:
```
https://cdn.ons.gov.uk/vendor/jquery/2.1.4/jquery.min.js
```

### Adding vendored libraries

To add new libraries to the CDN, add them to a new branch and
submit a pull request on GitHub.

The pull request will be reviewed by the ONS Website team.

Once the pull request has been merged, vendored code will be published
to the ONS CDN.

### Removing vendored libraries

To remove a vendored library, remove them in a branch and submit a
pull request on GitHub.

Please include the reason for removal.

We would not normally expect to remove vendored libraries since
it would be difficult to be certain they are no longer in use.

### Pull requests

Pull requests must meet some minimum requirements to be accepted:

* Include minified CSS and Javascript
* Include source map files and uncompressed CSS/Javascript where they're available
* Keep pull requests small - don't stockpile libraries to add in bulk!

### Need help?

E-mail the ONS Website team or ask us on Slack!

