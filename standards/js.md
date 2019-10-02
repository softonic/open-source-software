# JS Projects standards

The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

1. Every project MUST have [CODEOWNERS](https://help.github.com/en/articles/about-code-owners) file in the root folder
1. Every project MUST have LICENSE file in the root folder
1. Every project SHOULD have Travis and Scrutinizer integrations, with coverage and code quality
   1. Travis integration for NodeJS projects MUST test all the [supported NodeJS Versions](https://nodejs.org/en/about/releases/). This does not mean that the project must support all versions.
1. Every project MUST have a README file, that SHOULD have the following items:
   1. Title of the project
   1. Release badge
   1. License badge
   1. Build status badge
   1. Coverage badge
   1. Code quality badge
   1. Downloads badge
   1. Issue resolution time badge
   1. Open issues badge
   1. Installation instructions
   1. Documentation on usage
   1. Instructions for testing
   1. Instructions for contributing
   1. Link to license
1. Every project MUST have each release documented
2. Every project MUST follow the semver naming for versions
1. Every project MUST have package.json file in the root folder
1. Every project SHOULD NOT have package-lock.json nor yarn.lock files
1. Every project SHOULD have its code under the `src` folder
1. Every project SHOULD HAVE its tests under the `tests` folder
