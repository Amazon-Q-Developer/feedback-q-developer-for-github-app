## Changelog

### 2025-06-02
* PR reviews can be triggered with slash commands. You can initiate additional code reviews to iterate on your code using the /q review slash command. The code review is performed on the entire pull request's diff. [Initiating code reviews with Amazon Q Developer in GitHub pull requests](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/github-code-reviews.html)

#### 2025-05-14
* PR reviews will trigger only for PR open/reopen events. Auto PR reviews will not trigger when a PR/MR is updated. We are adding a way to manually trigger a review.

#### 2025-05-09

* Added the ability for the development agent to create / update to GitHub workflows.
* Enabled findings of all severities for PR reviews.
* Only show the top 10 findings for PR reviews, ranked by severity.
* Reduce the amount of text information provided by review, helping developers easily skim the findings.

#### 2025-05-05

* Public preview release of the [Amazon Q Developer for GitHub App](https://github.com/apps/amazon-q-developer) ([docs](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/amazon-q-for-github.html)).
