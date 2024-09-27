This repository is only used for github actions to interact with AWS CLI

One workflow is for s3 buckets, one of the jobs in this workflow creates a new buckets, lists buckets to see it exists, deletes the bucket and then lists again to see that it in fact got deleted.

## Remember
- [ ] If Glenn resets the AWS environment it's necessary to create a new access token for GH actions to access the AWS environment.
