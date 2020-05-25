# OCI Distribution Spec Conformance Results

---
<p><strong style="color: #bfac1d">⚠️ WARNING</strong></p>

The test results found on this page do not indicate OCI conformance (or lack thereof) for any of the listed registries.
This page is meant for informational purposes only.

---

Static HTML reports of [OCI Distribution Spec](https://github.com/opencontainers/distribution-spec) conformance tests run against various registries.

See any bad or missing information? You are encouraged to [submit a pull request](https://github.com/opencontainers/oci-conformance/blob/master/distribution-spec/README.md).

Test results are considered "verified" if a registry provider has submitted results to [oci-conformance](https://github.com/opencontainers/oci-conformance).

__Table of Contents:__

- [OCI Distribution Spec Conformance Results](#oci-distribution-spec-conformance-results)
  - [Commercial](#commercial)
    - [ACR](#acr)

## Commercial

### ACR

__Homepage:__ [https://azure.microsoft.com/en-us/services/container-registry/](https://azure.microsoft.com/en-us/services/container-registry/)

__Vendor:__ Microsoft

__Verified:__ no

__Test Results:__

| Workflow           | Status                                                                                                                                                               | Test Report                                                                                           | Job Definition                                                                                    |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Pull               | [![](https://github.com/shizhMSFT/oci-conformance/workflows/acr-1/badge.svg)](https://github.com/shizhMSFT/oci-conformance/actions?query=workflow%3Aacr-1) | [Link](https://shizhtest.blob.core.windows.net/distribution-spec/acr/pull/report.html)               | [Link](https://github.com/shizhMSFT/oci-conformance/blob/master/.github/workflows/acr_1.yml) |
| Push               | [![](https://github.com/shizhMSFT/oci-conformance/workflows/acr-2/badge.svg)](https://github.com/shizhMSFT/oci-conformance/actions?query=workflow%3Aacr-2) | [Link](https://shizhtest.blob.core.windows.net/distribution-spec/acr/push/report.html)               | [Link](https://github.com/shizhMSFT/oci-conformance/blob/master/.github/workflows/acr_2.yml) |
| Content Discovery  | [![](https://github.com/shizhMSFT/oci-conformance/workflows/acr-3/badge.svg)](https://github.com/shizhMSFT/oci-conformance/actions?query=workflow%3Aacr-3) | [Link](https://shizhtest.blob.core.windows.net/distribution-spec/acr/content-discovery/report.html)  | [Link](https://github.com/shizhMSFT/oci-conformance/blob/master/.github/workflows/acr_3.yml) |
| Content Management | [![](https://github.com/shizhMSFT/oci-conformance/workflows/acr-4/badge.svg)](https://github.com/shizhMSFT/oci-conformance/actions?query=workflow%3Aacr-4) | [Link](https://shizhtest.blob.core.windows.net/distribution-spec/acr/content-management/report.html) | [Link](https://github.com/shizhMSFT/oci-conformance/blob/master/.github/workflows/acr_4.yml) |
