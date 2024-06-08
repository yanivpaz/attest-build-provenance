echo eyJfdHlwZSI6Imh0dHBzOi8vaW4tdG90by5pby9TdGF0ZW1lbnQvdjEiLCJzdWJqZWN0IjpbeyJuYW1lIjoiMS50eHQiLCJkaWdlc3QiOnsic2hhMjU2IjoiYjllNjhlMWJlYTNlNWIxOWNhNmIyZjk4YjczYTU0YjczZGFhZmFhMjUwNDg0OTAyZTA5OTgyZTA3YTEyZTczMyJ9fV0sInByZWRpY2F0ZVR5cGUiOiJodHRwczovL3Nsc2EuZGV2L3Byb3ZlbmFuY2UvdjEiLCJwcmVkaWNhdGUiOnsiYnVpbGREZWZpbml0aW9uIjp7ImJ1aWxkVHlwZSI6Imh0dHBzOi8vc2xzYS1mcmFtZXdvcmsuZ2l0aHViLmlvL2dpdGh1Yi1hY3Rpb25zLWJ1aWxkdHlwZXMvd29ya2Zsb3cvdjEiLCJleHRlcm5hbFBhcmFtZXRlcnMiOnsid29ya2Zsb3ciOnsicmVmIjoicmVmcy9oZWFkcy9tYWluIiwicmVwb3NpdG9yeSI6Imh0dHBzOi8vZ2l0aHViLmNvbS95YW5pdnBhei9hdHRlc3QtYnVpbGQtcHJvdmVuYW5jZSIsInBhdGgiOiIuZ2l0aHViL3dvcmtmbG93cy9jaS55bWwifX0sImludGVybmFsUGFyYW1ldGVycyI6eyJnaXRodWIiOnsiZXZlbnRfbmFtZSI6InB1c2giLCJyZXBvc2l0b3J5X2lkIjoiODEyMjE0MzExIiwicmVwb3NpdG9yeV9vd25lcl9pZCI6IjQ5NTUzNTYifX0sInJlc29sdmVkRGVwZW5kZW5jaWVzIjpbeyJ1cmkiOiJnaXQraHR0cHM6Ly9naXRodWIuY29tL3lhbml2cGF6L2F0dGVzdC1idWlsZC1wcm92ZW5hbmNlQHJlZnMvaGVhZHMvbWFpbiIsImRpZ2VzdCI6eyJnaXRDb21taXQiOiJiNzY3YWVlODkwM2I3NmZhYzRlMDQ1OGFlOWZhNGZkNzBhMDhiMmVkIn19XX0sInJ1bkRldGFpbHMiOnsiYnVpbGRlciI6eyJpZCI6Imh0dHBzOi8vZ2l0aHViLmNvbS9hY3Rpb25zL3J1bm5lci9naXRodWItaG9zdGVkIn0sIm1ldGFkYXRhIjp7Imludm9jYXRpb25JZCI6Imh0dHBzOi8vZ2l0aHViLmNvbS95YW5pdnBhei9hdHRlc3QtYnVpbGQtcHJvdmVuYW5jZS9hY3Rpb25zL3J1bnMvOTQyNzgxODEzMC9hdHRlbXB0cy8xIn19fX0= | base64 -d | jq
```{
  "_type": "https://in-toto.io/Statement/v1",
  "subject": [
    {
      "name": "1.txt",
      "digest": {
        "sha256": "b9e68e1bea3e5b19ca6b2f98b73a54b73daafaa250484902e09982e07a12e733"
      }
    }
  ],
  "predicateType": "https://slsa.dev/provenance/v1",
  "predicate": {
    "buildDefinition": {
      "buildType": "https://slsa-framework.github.io/github-actions-buildtypes/workflow/v1",
      "externalParameters": {
        "workflow": {
          "ref": "refs/heads/main",
          "repository": "https://github.com/yanivpaz/attest-build-provenance",
          "path": ".github/workflows/ci.yml"
        }
      },
      "internalParameters": {
        "github": {
          "event_name": "push",
          "repository_id": "812214311",
          "repository_owner_id": "4955356"
        }
      },
      "resolvedDependencies": [
        {
          "uri": "git+https://github.com/yanivpaz/attest-build-provenance@refs/heads/main",
          "digest": {
            "gitCommit": "b767aee8903b76fac4e0458ae9fa4fd70a08b2ed"
          }
        }
      ]
    },
    "runDetails": {
      "builder": {
        "id": "https://github.com/actions/runner/github-hosted"
      },
      "metadata": {
        "invocationId": "https://github.com/yanivpaz/attest-build-provenance/actions/runs/9427818130/attempts/1"
      }
    }
  }
}
```
