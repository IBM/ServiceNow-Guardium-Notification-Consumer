## Contributing In General
Our project welcomes external contributions. To contribute code or documentation, please submit a [pull request](pulls).

A good way to familiarize yourself with the codebase and contribution process is
to look for and tackle low-hanging fruit in the  [issue tracker](issues).

### Proposing new features

If you would like to implement a new feature, please [raise an issue](issues) before creating a pull request so the feature can be discussed before spending your valuable time on it.

### Fixing bugs

If you would like to fix a bug, please [raise an issue](issues) before creating a
pull request so it can be tracked.

### Merge approval

The project maintainers use LGTM (Looks Good To Me) in comments on the code
review to indicate acceptance. A change requires LGTMs from one of the
maintainers.

For a list of the maintainers, see the [MAINTAINERS.md](MAINTAINERS.md) page.

## Creating a pull request

* Use a branch name that includes the issue number.
    ```
    git checkout -b issue-27
    ```
* Make fixes
* Commit change
    ```
    git add .
    git commit -m "issue-27: rename Database Catalog export"
    ```
* Push to the branch
    ```
    git push origin issue-27
    ```

* Create a Pull Request in the Web UI

_*For IBM employees*: To push to github.com under your personal github account, you will need to map your IBM account to your github account. [See this article](https://w3.ibm.com/developer/docs/open-source/contributing/) for more instructions. Then, if you authenticate with an SSH key, you will need to edit your ~/.ssh/config to use your personal github account for any interaction with github.com._


## Legal

Each source file must include a license header for the Apache
Software License 2.0. Using the SPDX format is the simplest approach.
For example: 

```
/*
Copyright <holder> All Rights Reserved.
SPDX-License-Identifier: Apache-2.0
*/
```

We have tried to make it as easy as possible to make contributions. This
applies to how we handle the legal aspects of contribution. We use the
same approach - the [Developer's Certificate of Origin 1.1 (DCO)](https://elinux.org/Developer_Certificate_Of_Origin) - that the Linux® Kernel uses to manage code contributions.

We simply ask that when submitting a patch for review, the developer
must include a sign-off statement in the commit message.

Here is an example Signed-off-by line, which indicates that the
submitter accepts the DCO:

```
Signed-off-by: John Doe <john.doe@example.com>
```

You can include this automatically when you commit a change to your
local git repository using the following command:

```
git commit -s
```

## Communication
Feel free to [create an issue](issues) to question or discuss anything with us. For more general questions regarding Guardium, we also refer you to the [IBM Security Guardium community](https://community.ibm.com/community/user/security/communities/community-home?CommunityKey=aa1a6549-4b51-421a-9c67-6dd41e65ef85).

