# Contributing to OpenEBS

Great!! We are always on the lookout for more OpenEBS hackers. You can get started by reading this [overview](./contribute/design/README.md)

Firstly, if you are unsure or afraid of anything, just ask or submit the issue or pull request anyways. You won't be yelled at for giving your best effort. The worst that can happen is that you'll be politely asked to change something. We appreciate any sort of contributions and don't want a wall of rules to get in the way of that.

However, for those individuals who want a bit more guidance on the best way to contribute to the project, read on. This document will cover all the points we're looking for in your contributions, raising your chances of quickly merging or addressing your contributions.

That said, OpenEBS is an innovation in Open Source. You are welcome to contribute in any way you can and all the help provided is very much appreciated.

- [Contributing to OpenEBS](#contributing-to-openebs)
  - [Raising Issues](#raising-issues)
  - [Submit Change to Improve Documentation](#submit-change-to-improve-documentation)
  - [Submit Proposals for New Features](#submit-proposals-for-new-features)
  - [Contributing to Source Code and Bug Fixes](#contributing-to-source-code-and-bug-fixes)
  - [Solve Existing Issues](#solve-existing-issues)
    - [Sign your work](#sign-your-work)
  - [Join our community](#join-our-community)

There are a few simple guidelines that you need to follow before providing your hacks.

## Raising Issues

When raising issues, please specify the following:

- Setup details need to be filled as specified in the issue template clearly for the reviewer to check.
- A scenario where the issue occurred (with details on how to reproduce it).
- Errors and log messages that are displayed by the software.
- Any other details that might be useful.

## Submit Change to Improve Documentation

Getting documentation right is hard! Refer to this [page](./contribute/CONTRIBUTING-TO-DEVELOPER-DOC.md) for more information on how you could improve the developer documentation by submitting pull requests with appropriate tags. Here's a [list of tags](./contribute/labels-of-issues.md) that could be used for the same. Help us keep our documentation clean, easy to understand, and accessible.

## Submit Proposals for New Features

There is always something more that is required, to make it easier to suit your use-cases. Feel free to join the discussion on new features or raise a PR with your proposed change.

- [Join OpenEBS community on Kubernetes Slack](https://kubernetes.slack.com) - Already signed up? Head to our discussions at [#openebs](https://kubernetes.slack.com/messages/openebs/)

## Contributing to Source Code and Bug Fixes

Provide PRs with appropriate tags for bug fixes or enhancements to the source code. For a list of tags that could be used, see [this](./contribute/labels-of-issues.md).

- For contributing to K8s demo, please refer to this [document](./contribute/CONTRIBUTING-TO-K8S-DEMO.md).
  - For checking out how OpenEBS works with K8s, refer to our [documentation](https://openebs.io/docs)

* For contributing to Kubernetes OpenEBS Provisioner, please refer to this [document](./contribute/CONTRIBUTING-TO-KUBERNETES-OPENEBS-PROVISIONER.md).

Refer to this [document](./contribute/design/code-structuring.md) for more information on code structuring and guidelines to follow on the same.

## Solve Existing Issues

Head over to [issues](https://github.com/openebs/openebs/issues) to find issues where help is needed from contributors. See our [list of labels guide](./contribute/labels-of-issues.md) to help you find issues that you can solve faster.

A person looking to contribute can take up an issue by claiming it as a comment/assign their GitHub ID to it. In case there is no PR or update in progress for a week on the said issue, then the issue reopens for anyone to take up again. We need to consider high priority issues/regressions where response time must be a day or so.

---

### Sign your work

We use the Developer Certificate of Origin (DCO) as an additional safeguard for the OpenEBS project. This is a well established and widely used mechanism to assure contributors have confirmed their right to license their contribution under the project's license. Please read [developer-certificate-of-origin](./contribute/developer-certificate-of-origin).

Please certify it by just adding a line to every git commit message. Any PR with Commits which does not have DCO Signoff will not be accepted:

```
  Signed-off-by: Random J Developer <random@developer.example.org>
```

or use the command `git commit -s -m "commit message comes here"` to sign-off on your commits.

Use your real name (sorry, no pseudonyms or anonymous contributions). If you set your `user.name` and `user.email` git configs, you can sign your commit automatically with `git commit -s`. You can also use git [aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) like `git config --global alias.ci 'commit -s'`. Now you can commit with `git ci` and the commit will be signed.

---

## Join our community

Want to actively develop and contribute to the OpenEBS community, refer to this [document](./community/README.md).
