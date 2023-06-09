# Parsec Project Roadmap

## Notes

- This roadmap document is a community resource. It is intended to help the project maintenance team
   to share and evolve a common understanding of the project roadmap with all contributors and
   stakeholders. It is for information purposes only, and it should be viewed as being both flexible
   and approximate.
- The release process for the Parsec project is documented
   [here](https://parallaxsecond.github.io/parsec-book/contributing/release_process.html).
- This roadmap document is focused on major/headline features and fixes. For full details and
   changelogs for historical releases, please refer to the [releases
   page](https://github.com/parallaxsecond/parsec/releases).
- Full details of the current cryptographic capabilities of Parsec on the various platforms are
   available
   [here](https://parallaxsecond.github.io/parsec-book/parsec_client/operations/service_api_coverage.html).
- The section on previous releases does not include any that were made before there was a defined
   process and cadence for Parsec releases. Full information about previous Parsec releases can be
   found on the [releases page](https://github.com/parallaxsecond/parsec/releases).

# Future Releases

## 1.3 (September 2023)

- This release is currently being scoped.

## Future Items (Not Assigned To Releases)

- Under construction!

# Previous Releases

## 1.2 (March 2023)

- Full [release page](https://github.com/parallaxsecond/parsec/releases/tag/1.2.0).
- Support for Debian packaging.
- Docker quick start package.
- Fixes for security reports.
- MSRV update.
- Minor improvements.

## 1.1 (September 2022)

- Full [release page](https://github.com/parallaxsecond/parsec/releases/tag/1.1.0).
- Random number generation supported in TPM and PKCS#11 providers.
- General fixes and improvements.

## 1.0 (March 2022)

- Full [release page](https://github.com/parallaxsecond/parsec/releases/tag/1.0.0).
- Supports storage of key metadata using [SQLite](https://www.sqlite.org/index.html).
- New [`CanDoCrypto`
   API](https://parallaxsecond.github.io/parsec-book/parsec_client/operations/can_do_crypto.html)
   for runtime queries of cryptographic capabilities. This API is currently experimental and subject
   to change.
- New [APIs](https://parallaxsecond.github.io/parsec-book/parsec_client/operations/attest_key.html)
   in support of key attestation flows. These APIs are currently experimental and subject to change.
   Currently supported for TPM platforms only.
- [Java client library](https://github.com/parallaxsecond/parsec-client-java) introduced, including
   integration with the Java Cryptography Architecture (JCA).
- Parsec CLI tool supports the creation of Certificate Signing Requests (CSRs).
- Integrates with [Trusted Services](https://www.trustedfirmware.org/projects/trusted-services/)
   from [trustedfirmware.org](https://www.trustedfirmware.org) on platforms where these services are
   available and functioning.

## 0.8.1 (September 2021)

- Full [release page](https://github.com/parallaxsecond/parsec/releases/tag/0.8.1).
- Support for [SPIFFE](https://spiffe.io)-based authentication to API operations. (Note: Rust client
   library only).
- Support for ECC keys in PKCS#11 devices.
- Support for secure elements using [CryptoAuthLib](https://github.com/MicrochipTech/cryptoauthlib).
- Fixes persistence of keys across reboot in TPM devices.
- TPM provider can be enabled/disabled dynamically based on detection of a TPM device.

*Copyright 2022 Contributors to the Parsec project.*
