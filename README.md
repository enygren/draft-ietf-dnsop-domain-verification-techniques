# Survey of Domain Verification Techniques using DNS

This is the working area for the individual Internet-Draft, "Survey of Domain Verification Techniques using DNS".

* [Editor's Copy](https://ShivanKaul.github.io/draft-sahib-domain-verification-techniques/#go.draft-sahib-domain-verification-techniques-latest.html)
* [Individual Draft](https://tools.ietf.org/html/draft-sahib-domain-verification-techniques-latest)
* [Compare Editor's Copy to Individual Draft](https://ShivanKaul.github.io/draft-sahib-domain-verification-techniques/#go.draft-sahib-domain-verification-techniques-latest.diff)

The repo uses Martin Thomson's [I-D template](https://github.com/martinthomson/i-d-template).

## Building the Draft

Formatted text and HTML versions of the draft can be built using `make`.

```sh
$ make
```

This requires that you have the necessary software installed.  See
[the instructions](https://github.com/martinthomson/i-d-template/blob/master/doc/SETUP.md). For this I-D, Markdown is the canonical source, so `kramdown-rfc2629` is what I use. This must be installed in addition to the right version of `make` and `xml2rfc` (yay, software) - please check the [SETUP doc](https://github.com/martinthomson/i-d-template/blob/master/doc/SETUP.md) for details. 

Also note that `main` is the default and working branch.

## Quick commands

Once you have everything set up correctly, the usual flow is:

```sh
$ make
```

This generates the `.txt` and `.html` outputs. 

To automatically fix lints:
```sh
$ make fix-lint
```

Then do a `git commit`. Note that a git commit will typically fail if the lint check fails.


## Contributing Guidelines

See the
[guidelines for contributions](https://github.com/ShivanKaul/draft-sahib-domain-verification-techniques/blob/main/CONTRIBUTING.md).
