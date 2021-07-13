[coc]: https://github.com/Readme-Workflows/.github/blob/main/.github/CODE_OF_CONDUCT.md
[discord]: https://discord.gg/2a9VC4AK6x
[release-drafter]: https://github.com/release-drafter/release-drafter

# Contributing to Readme-Workflows

The Readme-Workflows Organisation is home of various Open Source products that you can use and we're always happy about contributions, no matter how small they are.

With that said would we like to keep a set of Guidelines that you should follow. They allow us to keep a welcoming and supportive climate amongst our projects.

## Code of Conduct

We have a general [Code of Conduct][coc] that you need to follow. It ensures that everyone here is protected against harassment and targeted hate.  
By participating in any of our Projects do you agree to have read and understood the Code of Conduct and that not following it may get your access to the Projects blocked.

Any behaviour that goes against the Code of Conduct should be reported through E-Mail towards `baalkrshna[at]gmail.com` or `abhijoshi2k[at]gmail.com`, or alternatively through our [Discord Server][discord].

## General Guidelines

The following Guidelines are applied towards all projects of the Readme-Workflows Organisation without any limitations or restrictions.

Any project-specific requirements will be mentioned where necessary.

### Usage of Issue tracker

The issue tracker is reserved for Bug reports and Feature requests.  
Projects may have specific issue templates to use for those cases. Other topics such as general questions should be posted on appropriate places such as Discussions or our [Discord Server][discord].

### Pull requests

We use Pull requests to add new features, fix bugs, update dependencies and update documentation.

#### Status

The Pull request can have 3 different "states" which tell the maintainers about whether it is reviewable and/or mergable or not.

| Case                                     | Mergable? | Reviewable? |
| ---------------------------------------- | --------- | ----------- |
| `Draft Pull request`                     | No        | No          |
| `Pull request`                           | No        | Yes         |
| `Pull request w/ "Status: Ready" label`* | Yes       | Yes         |

* Please tell a maintainer when your Pull request is ready to merge, so that they can apply the `Status: Ready` label to it.

If at any point you think your Pull request isn't ready can you either change it back to a Draft or request the removal of the `Status: Ready` label.  
Only a normal Pull request with the `Status: Ready` label is allowed to be merged!

#### Title

The Pull request title should be short and simple, yet give a hint at what was done. A title such as `patch-1` doesn't give any clue about what was changed while a title like `Update incorrect default value` may give more info about something.  
The title is important as we use the [Release-Drafter Action][release-drafter] to automatically create and update Release Drafts and the action takes the Pull request title for the release.

#### Branch name

Similar to the title of a Pull request should the name of the source-branch have a good name.  
While we do not have a strict branch-pattern do we recommend to use `feature/<name>` for new features, `fix/<name>` for bug fixes and `docs/<name>` for updating documentation.
