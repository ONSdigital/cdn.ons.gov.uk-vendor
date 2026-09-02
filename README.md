# cdn.ons.gov.uk vendored libraries

Vendored third party CDN libraries for ONS web services.

## Using vendored libraries

The `vendor` directory in this repository is published to the CDN
under an equivalent `vendor` directory.

E.g., to include jQuery 2.1.4 (from [vendor/jquery/2.1.4](vendor/jquery/2.1.4)), you would
link to the file using the following URL:

```txt
https://cdn.ons.gov.uk/vendor/jquery/2.1.4/jquery.min.js
```

## Deprecated versions

These versions are still published, because we cannot be certain no service
depends on them, but they should not be used for new integrations. Prefer the
version listed under "Superseded by".

| Library | Version | Superseded by | Notes                                        |
| ------- | ------- | ------------- | -------------------------------------------- |
| mathjax | 2.6.0   | 2.7.9         | 2.7.9 is the final release of the MathJax 2 line |

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for details.

## Need help?

E-mail the ONS Dissemination team or ask us on Slack!

## Licence

Copyright ©‎ 2025, Office for National Statistics (<https://www.ons.gov.uk>)
