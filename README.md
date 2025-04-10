# DM Store Cron Helm Chart

Helm chart for the DM Store kubernetes job. It uses the [dm-store](https://github.com/hmcts/document-management-store-app) image to execute scheduled tasks by passing the arguments: `run [taskname]` to the jar.
