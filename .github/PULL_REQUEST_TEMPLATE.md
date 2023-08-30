# Merge checklist

Before merging your Pull Request, please make sure you have completed the following checklist:

- [ ] Deploy the PR to lab environment. Run `deploy <pr_url> to lab` in #actions-broker-ops slack channel 
- [ ] Test the End-to-End (E2E) on self-hosted environment. Queue a run here: [E2E-lab-self-hosted](https://github.com/github/actions-codespaces-test/actions/workflows/test-four-nines-lab.yaml)
- [ ] Test the E2E on hosted environment. Queue a run here: [Hosted-run](https://github.com/bbq-beets-four-nines/test/actions/workflows/test-hosted.yml?lab=true)

## Why is this important?

It is crucial to ensure that the changes made in the pull request do not break any existing functionality and work as expected in both self-hosted and hosted environments. By deploying the PR to a lab environment and testing the E2E, we can identify and fix any issues before merging the changes to the main branch.

Note: This is temporary checklist till we have better automated tests. 
