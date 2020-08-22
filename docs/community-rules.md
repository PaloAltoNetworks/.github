# Community Health Rules

**Palo Alto Networks Rules:**

- [Repository name](#repository-name)
- [Repository description](#repository-description)
- [License](#license)
- [README file](#readme-file)
- [Support file](#support-file)
- [Repository Topics](#repository-topics)
- [Contribution Guidelines](#contribution-guidelines)
- [Issue and PR Templates](#issue-and-pr-templates)

## Repository name

The repository name is too short or not descriptive enough.

Tips for better repository naming:

- **Avoid product acronyms** in repo names. For example, `prisma-access-sdk`
  instead of `pma-sdk`
- **Prefix the repo name with the technology** or framework you're building for,
  where appropriate. For example, a repo containing Terraform templates should
  be prefixed with `terraform-`.
- **Be descriptive**. For example, `azure-panos-arm-templates` instead of
  `azure`, or `xsoar-gcp-guide` instead of `xsoar-gcp`

Rename your repository in the repo settings. If you need help picking a name,
please reach out to the #github-questions channel on Slack.

## Repository description

The repository description field is too short or doesn't exist.

Fill in the description field for a repo with a meaningful description for
customers to understand the purpose of your repo. The description will show up
on https://gallery.pan.dev/gallery where customers can discover your repository.

You can find the description near the top of your repository page.

## License

The repository is missing a LICENSE file or the license in the file is not
recognized by GitHub.

**Easy fix:** Copy and paste this text into a file called `LICENSE` in the root
of your repo:

```
ISC License

Copyright (c) 2020, Palo Alto Networks Inc.

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

**Other license options:**

Create a file called `LICENSE` in the root of your repository. The file should
**not** have an extension. Use one of the following links to get the text for
this file. The text in the `LICENSE` file must be exact and be recognized by
GitHub to pass this check.

- [ISC License](https://choosealicense.com/licenses/isc/)
- [MIT License](https://choosealicense.com/licenses/mit/)

Palo Alto Networks uses these licenses for open source, but you can use a
license not listed here if there is a specific requirement to. Please get the
text for your chosen licenses at https://choosealicense.com.

## README file

The README.md file is missing or too short.

Create a file called `README.md` in the root of your repository. Case matters,
so `README.MD` does not count. The file must contain meaningful documentation of
the repository including any installation and usage instructions.

Here's some inspiration and templates to help you get started:

- [Palo Alto Networks README.md template](README.example.md)
- [How to write a good README](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
- [makeareadme.com](https://www.makeareadme.com/)

The README.md file will also appear in the Open Source Gallery at
https://gallery.pan.dev.

## Support file

The repository is missing a SUPPORT.md file, or the file does not contain the
official support language.

Create a file called `SUPPORT.md` in the root of your repository. Case matters,
so `SUPPORT.MD` does not count.

- The SUPPORT.md file **must** contain one of these legal-approved support
  messages (below).
- The SUPPORT.md file **should** be linked to from the README.md file (see the
  [README template](README.example.md#support) for an example).

SUPPORT.md file for **Community Supported** repositories:

```
Community Supported

The software and templates in the repo are released under an as-is, best effort,
support policy. This software should be seen as community supported and Palo
Alto Networks will contribute our expertise as and when possible. We do not
provide technical support or help in using or troubleshooting the components of
the project through our normal support options such as Palo Alto Networks
support teams, or ASC (Authorized Support Centers) partners and backline support
options. The underlying product used (the VM-Series firewall) by the scripts or
templates are still supported, but the support is only for the product
functionality and not for help in deploying or using the template or script
itself. Unless explicitly tagged, all projects or work posted in our GitHub
repository (at https://github.com/PaloAltoNetworks) or sites other than our
official Downloads page on https://support.paloaltonetworks.com are provided
under the best effort policy.
```

SUPPORT.md file for **TAC Supported** repositories:

```
Palo Alto Networks Supported

The software and templates in this repo are released under the official support
policy of Palo Alto Networks through the support options that you've purchased,
for example Premium Support, support teams, or ASC (Authorized Support Centers)
partners and Premium Partner Support options. The support scope is restricted to
troubleshooting for the stated/intended use cases and product versions specified
in the project documentation and does not cover customization of the scripts or
templates.
```

## Repository Topics

The repository is missing a product topic. Topics are like tags for GitHub repos
which help customers discover repos they're interested in.

To help customers discover and understand your repo, please follow these topic
guidelines:

- Repositories **must** have at least one Palo Alto Networks product topic (see
  the list below)
- Repositories **should** have topics for every related technology. For example,
  a Terraform template for PAN-OS would have these topics: `pan-os` `terraform`
- Repositories **can** use any other topics that help customers discover your
  repo.

Required product topics (use at least one):

- `autofocus`
- `cloud-services`
- `cortex`
- `cortex-data-lake`
- `cortex-xdr`
- `cortex-xdr-analytics`
- `cortex-xdr-investigation-and-response`
- `demisto`
- `directory-sync-service`
- `evident`
- `globalprotect`
- `hardware`
- `hub`
- `log-forwarding-app`
- `logging-service`
- `pan-os`
- `panorama`
- `prisma-access`
- `prisma-cloud`
- `prisma-cloud-compute-edition`
- `prisma-saas`
- `secdo`
- `security-lifecycle-review-slr`
- `traps`
- `traps-management-service`
- `vm-series`
- `wildfire`

Topics are also used for discovering and filtering repos at
https://gallery.pan.dev.

## Contribution Guidelines

This is **optional**

All repositories use the default contribution guidelines at
https://github.com/PaloAltoNetworks/.github/CONTRIBUTING.md. If you need to
customize your contribution guidelines, please create your own `CONTRIBUTING.md`
file in the root of your repository. The file must be at least 200 characters.

## Issue and PR Templates

This is **optional**

The repository is using the default Palo Alto Networks Issue and Pull Request
Templates located at
https://github.com/PaloAltoNetworks/.github/tree/master/.github.

You can create a custom Issue or Pull Request Template to customize the
questions asked of customers and other developers when they open a GitHub issue
or PR.

More information:

- [Issue Templates](https://help.github.com/en/github/building-a-strong-community/configuring-issue-templates-for-your-repository)
- [Pull Request Templates](https://help.github.com/en/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository)

Note: If you'd like to suggest a change to the default Issue and Pull Request
templates to improve them across all repositories, please fork and create a pull
request against this repo: https://github.com/PaloAltoNetworks/.github.
