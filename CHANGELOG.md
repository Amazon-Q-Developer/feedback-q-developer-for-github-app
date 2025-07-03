## Changelog

#### 2025-07-03
* Added the /q help command for developers to quickly check what Q commands are available
  
#### 2025-07-02
* Enabled support for top-level pull request feedback when iterating on a pull request with the Q Developer agent
* Added transparency for background tasks when working with Q Developer on an issue
* Raised word count limits for comments and issues when working with Q Developer agent
* Bug fixes addressing silent failure of Q Developer agent, due to permission issues

#### 2025-06-27
* Added custom project rules support for enforcing project-specific code standards and best practices when Q is invoked to perform feature development. [Creating Project Rules for Amazon Q Developer](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/third-party-context-project-rules.html)

#### 2025-06-13
* Bug fixes addressing issues in the Q Developer Software Agent experience, including:
  - Code generation outputs misalignment with pull request descriptions
  - Inconsistencies in code iteration that were causing import statement placement issues

#### 2025-06-10
* Code transforms and the Q Developer agent can now be triggered with slash commands. When creating an issue or configuring an existing issue, you can trigger the Q Developer agent by issuing /q dev slash command. Also you can initiate java upgrade using the /q transform slash command in an issue. [Amazon Q Developer agents](https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/amazon-q-for-github.html#github-agents)

#### 2025-06-02
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
