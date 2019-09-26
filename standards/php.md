# PHP Projects standards

The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

1. Every project MUST have [CODEOWNERS](https://help.github.com/en/articles/about-code-owners) file in the root folder 
2. Every project MUST have LICENSE file in the root folder
3. Every project SHOULD have travis integration, with coverage and code quality
..*. travis integration MUST test all the [supported PHP Versions](https://www.php.net/supported-versions.php) . This does not mean that the project must support all versions.
3. Every project MUST have a README file, that SHOULD have the following items:
..1. Title of the project 
..2. Release icon
..3. License icon
..4. Build status icon
..5. Coverage icon
..6. Code quality icon
..7. Downloads icon
..8. Installation instructions
..9. Documentations on usage
..10. Instructions for testing
..11. Link to license
4. Every project MUST have composer.json file in the root folder
5. Every project SHOULD have its code under the `src` folder
6. Every project SHOULD HAVE its tests under the `tests` folder
