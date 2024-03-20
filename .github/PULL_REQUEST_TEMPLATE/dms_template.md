<!--
  This pull request updates the configuration of our DMS replication task, which migrates tables from our production database to Redshift.

  Explain the change here or in a linked Jira Issue.
-->

Jira Issue:

## PR Checklist

_Completed by submitter, verified by reviewer_

- [ ] Any columns containing PII are noted here or in the attached Jira Issue
- [ ] Columns with PII have good reason to be replicated (otherwise exclude them)
- [ ] Tables with PII are replicated to the appropriate `*-pii` schema
