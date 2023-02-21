# W3C Patent Policy

This repository contains the [Bikeshed](https://speced.github.io/bikeshed/) source files
for the [W3C Patent Policy](https://www.w3.org/Consortium/Patent-Policy/).

## Governance

Formally,
the evolution of the W3C Patent Policy is defined by the [Process Evolution](https://www.w3.org/Consortium/Process/#GAProcess) section
of the [W3C Process Document](https://www.w3.org/Consortium/Process/),
which places it under the management of the [Advisory Board](https://www.w3.org/Consortium/Process/#advisory-board),
with approval of new versions through [Advisory Committee Review](https://www.w3.org/Consortium/Process/advisory-committee-review).

In practice,
discussions about the W3C Patent Policy and potential changes to it
happen in the [W3C Patents and Standards Interest Group (PSIG)](https://www.w3.org/2004/pp/psig/).
PSIG also maintains the [W3C Patent Policy FAQ](https://www.w3.org/2020/09/15-pp-faq.html).

## Contributing

<em>This repository is not open for comments or pull requests.</em>
Contributions are expected to be made via [PSIG](https://www.w3.org/2004/pp/psig/);
please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Technical details

Prior to the 2020 version of this document,
it was written directly in HTML.
For ease of editing and in order to generate a document
with more modern styling and conveniences
(such as cross linking, an auto-generated table of content, indexes…),
the 2017 Patent Policy HTML file was converted to use the [Bikeshed](https://speced.github.io/bikeshed/) preprocessor.
Further changes were made against that basis.

The `index.bs` and `*.include` files in this repository are this source.
`index.html` is the result of building this document using `bikeshed spec`.
(See Bikeshed’s documentation for [installation instructions](https://speced.github.io/bikeshed/#installing)).
This repository include no server-side continuous integration system,
therefore `index.html` must be manually generated
and committed together with any source change.

## Differences from the published version

At the time of writing,
aside from the status section and some publication-related meta-data,
<em>this document is textually identical to the published and operative version of the W3C Patent Policy</em>.

(There are some minor differences in the source formatting of `index.html`
and in the associated CSS,
due to artefacts of publishing,
as well as to using more recent a more recent version of Bikeshed.)
