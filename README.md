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
| `latest` | `sha256:a90b8067089ee0a1c3ad54c9ea971ede8592ccb5120b7835a5b0426c94ccf59f`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a90b8067089ee0a1c3ad54c9ea971ede8592ccb5120b7835a5b0426c94ccf59f) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:a90b8067089ee0a1c3ad54c9ea971ede8592ccb5120b7835a5b0426c94ccf59f"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "fdd6627997304dea2a6d5be8ab311d8370192f57",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCICTdDwLJS9I6erD4rxJuZO6UPLOOGX+cJrtB5pvtKJ+ZAiEAsHGKMfZraPlK1C7RpN7GGiNO2o0EjPQsPfkkmuQ5awg=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIxOTExN2RjYjU5YjAyYzAzMGNjMDdhZmE4NzQ0MTdlYzM4ODlkNzdiN2RhMWQ3NzU3YTU5NWI4NDVkYTAwOWRiIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQm80T1ZNbHYyZ3NVam14VkQ3Zy9hQWlqNFNJVlRSYUd6RmdsYzY3UGd4d0FpRUEvMjBFZGw5Y3JQczMvRG5Jd2J6cm02RnpMMFh3b0J2YjZnTUFmMVUzZHlRPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwWFowRjNTVUpCWjBsVlMyZHRaa2tyV1RReGJXRlBXRFpxU1ZnelZUTXpWak5pVmpKamQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlROTlJFa3hUbFJGTUZkb1kwNU5ha2w0VFVSRk0wMUVUWGRPVkVVd1YycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZyVlhvNFRtWlFSVlJYVUZaUk9FMXRValZzVGtZelNGSnlWWEptUjBScmRYZzFXbFFLV2xCMVNqUkNXV0ZsVTFReGJVVjNWSEJrVFZjMWNYcDRNVzF2UjJkdFNVcGlTa05rYkVoUlUzRk1jMmh2VmpSU0wyRlBRMEZzVVhkblowcFJUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZVVkRVM0NtRnVVWGhXWkZkaU9GZG1SRnBDZERKd2VTdGFUMmxyZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUcxYVIxRXlUbXBKTTA5VWF6Tk5la0V3V2tkV2FFMXRSVEphUkZacFdsUm9hRmxxVFhoTlYxRTBDazE2WTNkTlZHdDVXbXBWTTAxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwWjFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT0VKSWIwRmxRVUl5UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtY3JVR1ExTjNOQlFVRlJSRUZGWTNkU1VVbG9RVXBHUTBoS2VTOEtRWFZEYUd4NFVWUnBlRlJYVjBzMGNuWnJkMFZsYUdGbU1FZEdOWEpwZERZMWVXTjBRV2xDV2pkbVNEZGpWMXB4Y2xBelN6UnZVVUpCZHl0RGRWVlJaZ3AyTjJFeE4ybEdUSEExUlVneEwyWXhVMVJCUzBKblozRm9hMnBQVUZGUlJFRjNUbTlCUkVKc1FXcEJVVUZWU1RKYUswcGlhRWR1WVdGVlEwTnVlWEJzQ2pjNFNUZFVhMDVoUkU1TFoyTkhRVkE0U0ZvMlowZDRhME5UTDJkb1FuQmhVVWRIY0VaRFJUSlNiMVZEVFZGRFdFMWhURFV3Vm1ReWNsVnVVbU53VkhvS1FtOVdaRGxaZDJsaGNtVTNTa1owZEVOVlUybFRlalpOV0RWeVJWcHRZMlpqVEROa1l6QXpOVlJWVEdaRFExRTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665975337,
          "logIndex": 5251461,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "fdd6627997304dea2a6d5be8ab311d8370192f57",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3262032135",
      "sha": "fdd6627997304dea2a6d5be8ab311d8370192f57"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

