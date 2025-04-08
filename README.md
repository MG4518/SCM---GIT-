# SCM---GIT
# What is version control?
Version control, also known as source control, is the practice of tracking and managing changes to software code.
Version control systems are software tools that help software teams manage changes to source code over time. 
As development environments have accelerated, version control systems help software teams work faster and smarter. 
They are especially useful for DevOps teams since they help them to reduce development time and increase successful deployments.

Version control software keeps track of every modification to the code in a special kind of database.
If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

# Source code management
Source code management (SCM) is used to track modifications to a source code repository. SCM tracks a running history of changes to a code base and helps resolve conflicts when merging updates from multiple contributors. SCM is also synonymous with Version control. 

# The importance of source code management tools
When multiple developers are working within a shared codebase it is a common occurrence to make edits to a shared piece of code. Separate developers may be working on a seemingly isolated feature, however this feature may use a shared code module. Therefore developer 1 working on Feature 1 could make some edits and find out later that Developer 2 working on Feature 2 has conflicting edits.

Before the adoption of SCM this was a nightmare scenario
Developer 1 would make edits and Developer 2 would unknowingly save over Developer 1’s work and wipe out the changes. SCM’s role as a protection mechanism against this specific scenario is known as Version Control.

# What is Git?
Git is a distributed version control system used to track changes in source code during software development. It helps developers collaborate, manage different versions of code, and keep track of changes over time.

Here’s a quick breakdown of what Git does:
✅ Version Control: Keeps a history of all changes made to code files.
✅ Collaboration: Allows multiple developers to work on the same project simultaneously without overwriting each other’s work.
✅ Branching and Merging: Lets you create branches to try out new features or fix bugs, then merge them back into the main code when ready.
✅ Distributed System: Every developer has a full copy of the project history, not just the latest version. This makes Git fast and reliable, even when offline.

Git was created by Linus Torvalds in 2005, mainly for developing the Linux kernel.

# GitHub Features for Integration

GitHub Actions: Built-in CI/CD for automation
Pull Requests: Review and merge changes
Webhooks: Trigger events like Jenkins jobs, Slack messages, etc.
Integration with tools: Jira, Jenkins, VS Code, Terraform, etc.
