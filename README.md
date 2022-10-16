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
| `latest` | `sha256:30033b0d4747b81c8fc5667b29c0d7111d79abd30a115730a4806d496f61d87f`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:30033b0d4747b81c8fc5667b29c0d7111d79abd30a115730a4806d496f61d87f) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:30033b0d4747b81c8fc5667b29c0d7111d79abd30a115730a4806d496f61d87f"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "e8d47d7aa0a88faa6c59be7b155ffa392ab9fb14",
      "1.3.6.1.4.1.57264.1.4": "Create Release",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/template",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCts84OP2l/In5ZiwJ2EUOdllJiNpuqmZxCEu0wh3RyNwIgRBAmwwcDdPwRfOJMmEyTSaUE99qJClvErQeSDL/OcII=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIxMzllODJiNGIxNTY4NDg1MTNjNzI2NjcwYTkxMzlmNGRiMjQ1ZGM1Zjg3NDJiYmIwMjBiNTMyNTQ1M2FmOTU4In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJQm1kUU9BMGJvSjJEenZWNnl2bm94NEdXQWpxZW9QSHJUU2t6c01WNExRVkFpRUF1c08vaGJPaytBVDBLNlZYUWxFRWFuSERBUENta3NaMU1TRjV0eHpyaDI0PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUnlla05EUVhwaFowRjNTVUpCWjBsVlkwOUxUWGRwTmpCNWNXRXpPWFJpTTJKSFRuaEdabTFhVFVOUmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFFUlRGTlJFa3dUbXBOZUZkb1kwNU5ha2w0VFVSRk1VMUVTVEZPYWsxNFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZUV0hoRFJ6aG1iMGhHUzBZM1Z6UmFSR0ZvU0ZCMmJXUnZaRFZOZVdSa1ExaHlXRW9LUjNneU5XVlBURzVEVEhaTkswc3pObTVVV0M5M2FGQlFiMmhoTVRScFpVY3hUblkzZFc1VlZIbHZObFphV1VGcVJqWlBRMEZzVlhkblowcFNUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZNVWtGYUNrZDNVSG8wZEN0dk1HcHlUa3hPSzBSekwxbzVOVVZGZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGbldVUldVakJTUVZGSUwwSkhRWGRZYjFwallVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d6VW14aVdFSnpXVmhTYkV4NU5XNWhXRkp2WkZkSmRtUXlPWGxoTWxwellqTmtla3d6U214aVIxWm9ZekpWZFdWWFJuUmlSVUo1Q2xwWFducE1NbWhzV1ZkU2Vrd3lNV2hoVnpSM1QxRlpTMHQzV1VKQ1FVZEVkbnBCUWtGUlVYSmhTRkl3WTBoTk5reDVPVEJpTW5Sc1ltazFhRmt6VW5BS1lqSTFla3h0WkhCa1IyZ3hXVzVXZWxwWVNtcGlNalV3V2xjMU1FeHRUblppVkVGWFFtZHZja0puUlVWQldVOHZUVUZGUTBKQmFIcFpNbWhzV2toV2N3cGFWRUV5UW1kdmNrSm5SVVZCV1U4dlRVRkZSRUpEYUd4UFIxRXdUakpSTTFsWFJYZFpWR2MwV20xR2FFNXRUVEZQVjBwc1RqSkplRTVVVm0xYWJVVjZDazlVU21oWmFteHRXV3BGTUUxQ2QwZERhWE5IUVZGUlFtYzNPSGRCVVZGRlJHdE9lVnBYUmpCYVUwSlRXbGQ0YkZsWVRteE5RMmRIUTJselIwRlJVVUlLWnpjNGQwRlJWVVZIYlU1dldWZHNkVm96Vm1oamJWRjBZVmN4YUZveVZucE1NMUpzWWxoQ2MxbFlVbXhOUWpCSFEybHpSMEZSVVVKbk56aDNRVkZaUlFwRU0wcHNXbTVOZG1GSFZtaGFTRTEyWWxkR2NHSnFRMEpwZDFsTFMzZFpRa0pCU0ZkbFVVbEZRV2RTT1VKSWMwRmxVVUl6UVVGb1oydDJRVzlWZGpsdkNsSmtTRkpoZVdWRmJrVldia2RMZDFkUVkwMDBNRzB6YlhaRFNVZE9iVGw1UVVGQlFtYzViVXBPY1dOQlFVRlJSRUZGWjNkU1owbG9RVkJUWW10aFkyWUtUbTFTZFdVMlJUWnFTMDB3UkhCR1FXeHZaa2hyTm1wTk5TOVpMMWxIWjJKdFRXMVdRV2xGUVN0bmFWQnNhbUp5YVdkUVpYTnVOWFpEWWxSeWIxRldiZ3AzTUZSSmJuWm9Vbk5uWm1SV1pXTjZhRTVKZDBObldVbExiMXBKZW1vd1JVRjNUVVJhZDBGM1drRkpkMGxVYTFaNVdrOU5WSGd2UVRCeVRHdFFWbmdyQ20xR1ZteG9UV3BLT0hZeE5rTkpNazlrU1RJMU0xUm1NbWx6VUV0UFdrZGhLM28yV1dKYVVFUm1UMDQ1UVdwQlJtbHpiRVpTYTNRM2VreHVhREJxWjBrS05uSTBZbE50Tm5ocmRXNVpNMGgzTkVaR01EaHNjVnBYWldOQlptbFFhVTUwU214VlYzRjJVMWQ0TWpKS1VFRTlDaTB0TFMwdFJVNUVJRU5GVWxSSlJrbERRVlJGTFMwdExTMEsifX19fQ==",
          "integratedTime": 1665802032,
          "logIndex": 5131616,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/template/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": "Create Release",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/template",
      "githubWorkflowSha": "e8d47d7aa0a88faa6c59be7b155ffa392ab9fb14",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "3254145015",
      "sha": "e8d47d7aa0a88faa6c59be7b155ffa392ab9fb14"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

