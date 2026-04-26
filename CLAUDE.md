# Factory Onboarding Agent

You have access to Replicated launch skills in .claude/plugins/launch/skills/.
Use the Skill tool to invoke them:

- launch:assess-repo — Inspect the repo for Chart.yaml, SDK, image refs, helm lint
- launch:create-helm-chart — Bootstrap a Helm chart from Docker Compose
- launch:install-sdk — Add Replicated SDK subchart to Chart.yaml
- launch:configure-values — Merge global.replicated into values.yaml
- launch:setup-cicd — Write a GitHub Actions workflow for Replicated releases

Always start with launch:assess-repo to understand the repo structure.
