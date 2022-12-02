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
| `latest` | `sha256:317848ff4e0ed8531591eb1992fcd037dc63a45647a281144a5dff5435ce901b`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:317848ff4e0ed8531591eb1992fcd037dc63a45647a281144a5dff5435ce901b) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:317848ff4e0ed8531591eb1992fcd037dc63a45647a281144a5dff5435ce901b"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "ce38412df92d7ae8e42c1dcfedf62959e14f76a4",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEQCIFCnWnQFMrz/gkzjXmKdhIIbWpSG0EnknRCd9L93nAkbAiAM54D8CA3y/9gmaR1bUIvhqahg4THm4GMVLM4SOgHWnA==",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2YjhkNDViNTgxN2FhMTk5ZDc5Y2YxNjIzNmNlNjUxMjg4YWYxMzMxZDI2ZGNjNTEzZmE1YTU1YmQ4NzYzZTYyIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQm9nUndJcDljVVhhc2dWZENjOTByT3l5T0dYcS9qbVg1Q0pqWGhmQW1vOUFpRUFuZFRDRFZJOXBGQ05Xais0YStELzdLM2dBck5heXYyR0p1UktSQ1NYT2o0PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlha05EUVhwVFowRjNTVUpCWjBsVlJpOVZNazA0V2poVFlXbEpTSGRUUjNvMmVFNXFOM28wTDBGVmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVhoTlJFRjVUMFJCTWxkb1kwNU5ha2w0VFdwQmVFMUVRWHBQUkVFeVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZLWldkaWVGTnBVVTVsVVVWRGFXeGpjMlUzWjJwMWNFMUtjMHBOYkhOaWVtdGpkMm9LYkhoWVFrczBhVk5pTVdNdlpFSmlSVkZOWkZaeFVGZGpiRU5yZFdoclJrRkJPRXBLZFVneGFYSXlhMWx2WTJFeGFUWlBRMEZzVFhkblowcFFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZQZEhwdENsQmlOR3hQWjFFcldEWjNUbmcxZDI4eGRFeERiWFZOZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUdwYVZFMDBUa1JGZVZwSFdUVk5iVkV6V1ZkVk5GcFVVWGxaZWtacldUSmFiRnBIV1RKTmFtc3hDazlYVlhoT1Ixa3pUbTFGTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwVVZsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTTjBKSWEwRmtkMEl4UVU0d09VMUhja2Q0ZUVWNUNsbDRhMlZJU214dVRuZExhVk5zTmpRemFubDBMelJsUzJOdlFYWkxaVFpQUVVGQlFtaE5jMVpaV2tGQlFVRlJSRUZGV1hkU1FVbG5UR1JHZEc1YVdqWUtjMmRRVXpsTFNEWTFabUp3TjBaalRFaFhRMUpVV2sxV1RqUktZbTV1U21ObGVqQkRTVVVyZEdoUlpuSm9lRUpVVkdReFltMXlOVXBKYlhkWFdpOVlkUW8yYm5CMU9VVlNkbnBaZDNONE9IRjFUVUZ2UjBORGNVZFRUVFE1UWtGTlJFRXlaMEZOUjFWRFRWRkVRbXd6YkhsRFNDOHhRWHBzU1VoeWVqTk1OMkUxQ2k5RlUwcHJMMHBEU2l0amJFTkhiM0J4YVdOWk1sQjVUVmhrSzNKc2RUWklTWGQxVVRaUlZUazRObmREVFVKdmFqVnpTa3h3V0VWbU9XVnBXak5DTVRVS01td3lkRUpIVVRkbmJXUkxlRkp4VTBSSllXdFRUa0ZVYTNkV0x6bHFaRTFMU0hCRVRFOHZSWFJhT0dRNWR6MDlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1669854511,
          "logIndex": 8189214,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "ce38412df92d7ae8e42c1dcfedf62959e14f76a4",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3588267464",
      "sha": "ce38412df92d7ae8e42c1dcfedf62959e14f76a4"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

