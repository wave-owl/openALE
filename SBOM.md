# Source SBOM

**Initial source snapshot, not a release report.** Source commit `1f0fb89a4b3c9cd6b6cbb0a41e7ae8f817377b48` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/openALE `1f0fb89a4b3c9cd6b6cbb0a41e7ae8f817377b48`

- sbom:role: source-root
- sbom:git-commit: 1f0fb89a4b3c9cd6b6cbb0a41e7ae8f817377b48
- sbom:git-tree: b4091aa5556c8c61b701a97d23bcd4ab828af772
- sbom:source-repository: https://github.com/wave-owl/openALE
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE", "sha256": "eca2f4f48df66a3a763aec409b47602514349759665d4147f5e8bda7fbb79fc2"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/openALE | 1f0fb89a4b3c9cd6b6cbb0a41e7ae8f817377b48 | source-root | unresolved; manual review required |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| mbedtls | unresolved | conditional-build-requirement | unresolved |
| third_party | unresolved | declared-vendored-source | unresolved; manual review required |
| Conditional source requirements declared by CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by ale_monitor/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by tools/location-relay-server/package.json | unresolved | conditional-build-runtime-requirement | unresolved |
| Hamlib optional | unresolved | conditional-build-runtime-requirement | unresolved |
| FetchContent mbedTLS tag mbedtls-3.6.7 | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
