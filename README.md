# AzureTestEnv

```json
azure login
azure config mode arm

azure group create -n PR-RG1 -l "UK West"
azure group deployment create -f <PathToTemplate>\createTestEnvTemplate.json -e <PathToParameterFile>\createTestEnvParams.json -g PR-RG1 -n DeployTestEnv1
```

You will need to supply the database password at deploy time.
