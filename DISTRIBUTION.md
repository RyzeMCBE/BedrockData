# Composer distribution

This public fork is published under the Composer package name `ryzemcbe/bedrock-data`.

Once the package has been registered on [Packagist](https://packagist.org/) and a tested release tag exists, developers can install it with:

```bash
composer require ryzemcbe/bedrock-data:<tested-release-version>
```

Data files and paths are unchanged so consumers can keep using existing resource lookup paths.

The package declares an upstream package replacement at `self.version`; it is not a promise that all upstream versions have identical APIs.

Data releases should be tagged only after the matching BedrockProtocol revision and RyzeMP code-generation tests pass.

**Release checklist:** validate `composer.json`, run dependency tests, create a SemVer tag, register/update this public GitHub repository in Packagist, and verify a clean installation without custom VCS configuration. Tags and Packagist registration are separate operations.
