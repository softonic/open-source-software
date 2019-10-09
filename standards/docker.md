# Docker Projects standards

The key words “MUST”, “MUST NOT”, “REQUIRED”, “SHALL”, “SHALL NOT”, “SHOULD”, “SHOULD NOT”, “RECOMMENDED”, “MAY”, and “OPTIONAL” in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

1. Every project MUST have [CODEOWNERS](https://help.github.com/en/articles/about-code-owners) file in the root folder 
1. Every project MUST have LICENSE file in the root folder
1. Every project MUST have a README file, that SHOULD have the following items:
   1. Release icon
   1. License icon
   1. Docker Automated build icon
   1. Build status icon
   1. Docker pulls icon
   1. Docker stars icon
   1. Docker Layers icon
   1. Docker image size icon
   1. Issue resolution time icon
   1. Open issues icon
   1. Title of the project
   1. Overview of the project
   1. Documentations on usage
1. Every project MUST have Dockerfile file in the root folder
1. Every project SHOULD have all files copied in the image under `rootfs` folder
