# template

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/jdolitsky/template/actions/workflows/release.yaml/badge.svg)](https://github.com/jdolitsky/template/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/template:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `latest` | `sha256:a6765eda4508301003a0fe4682d648a5b5c015e56c4f577173ab70eb66672330`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a6765eda4508301003a0fe4682d648a5b5c015e56c4f577173ab70eb66672330) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


## Usage

WORK IN PROGRESS


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/template:latest | jq
```

Output:
```
Verification for cgr.dev/chainguard/template:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/template"
      },
      "image": {
        "docker-manifest-digest": "sha256:a6765eda4508301003a0fe4682d648a5b5c015e56c4f577173ab70eb66672330"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "7c6c469ba11a0eae335fe9090af68273116bd050",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQDsvNKXPbywSiUZY5sQVh1GOeIxesHFQ9vdMwVbqYk6xgIhAJPCV26pdRaoK5OPvRqcQlEa6AUBvhAQy216jGeXBW1Z",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJlYmI1OGU5NWU0OWE2ZGZjYzg4MWM3NzJmZDEyMWRkMzQxNmQzYzEyNzU3YmU2NzljNWI1OGM2YjFmODg4MmNkIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUNtMG03NHFLWFZhVGtRdjJ0WExlcVhDejhZMGN1VTdBa3p1QjdwOWpVb3hRSWhBSWIyeCtKNzFvV2Z0Z1EzWVFCMjFBYThZRFF3K1ZkYWllUlU5ekF4VFd0MyIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlR6QkxVM2M0VUhSS0sxWTNVSFFyT0hFeGRqZEhlV0YwWm1rNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVhwTlJFRjVUVlJGTlZkb1kwNU5ha2w0VFdwQmVrMUVRWHBOVkVVMVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZFTXpOQk1GSXdaRlF4WjFoeVEwZE5jWFZGY0UxbWJYaEhhVmRsTlZBelZHRTVORVFLU21ReksyMVJORzFFZUdGNmFsWTJlRWxwWmtsWGNVeGtUMGhVY0ZSV1Vpc3lPVEZOTWpKc05ESjBjRlYyZURSUVdrdFBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZzZEd4bENreHdkbVY0TDFsSGFHbHRSVWxxTWxab1NuTXJiVEZaZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEWnpOWmVscHFUa1JaTlZsdFJYaE5WMFYzV2xkR2JFMTZUVEZhYlZVMVRVUnJkMWxYV1RKUFJFa3pDazE2UlhoT2JVcHJUVVJWZDAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE9WbUkwTWtWQlFVRlJSRUZGWTNkU1VVbG5SM2hXYUZwQmVHVUtaV2xuTTFST2VqRjVRVTFzWkhGNldpOU9SR1Y2ZW01WGRDOXlhR1JSUkVaWmEwVkRTVkZFUW5wQmNYVmliMlYyY0M5VWIzQldWV0UzVkV4Qk1uTnRSUXB6V2tsaWVVdGhhMFp4VVhsUlpVUlVNRlJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEJhek5LT0doWWJVeE5NMGQwV25CdmRtNU9jWEFyQ25aSWRYSk1lalI1ZFhwR2RIWlRPSEV3YUdNMU4xQmhPVU5PZVZCd2FGQmFVMlZUVUc1eUwyVnBMMVZEVFZGRVF6Uk1ZVk5RTW5ONlVXdE9WVlZJWWtZS1NVbFFjRnBPZVhBd2NqVlNhVkk0YWtNd1ZtUjVjbk16YjNsUWFFdzViWGRaUkZwbWNIWndUVmRYUWt4R2RVazlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1670026900,
          "logIndex": 8326357,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "7c6c469ba11a0eae335fe9090af68273116bd050",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3606062311",
      "sha": "7c6c469ba11a0eae335fe9090af68273116bd050"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

