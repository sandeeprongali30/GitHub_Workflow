# GitHub_Workflow
GitHub_Workflow explaining workflow_dispatch

-->curl command to trigger workflow dispatch

curl -X POST https://api.github.com/repos///actions/workflows/workflow_dispatch.yml/dispatches -H "Accept: application/vnd.github+json" -H "Authorization: Bearer " -H "X-GitHub-Api-Version: 2022-11-28" -H 'Content-Type: application/json' -d '{"ref":"dev","inputs":{"userName": "myuser", "userId": "23456kjhgsdfg", "siteName": "London"}}
