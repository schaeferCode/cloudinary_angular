# Contributing to Cloudinary Angular SDK

Contributions are welcome and greatly appreciated!

## Reporting a bug

- Ensure that the bug was not already reported by searching in GitHub under [Issues](https://github.com/cloudinary/cloudinary-angular-2/issues) and the Cloudinary [Support forms](https://support.cloudinary.com).
- If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/cloudinary/cloudinary-angular-2/issues/new).
  Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.
- If you require assistance in the implementation of the Cloudinary Angular SDK please [submit a support request](https://support.cloudinary.com/hc/en-us/requests/new) in the Cloudinary web site.

## Requesting a feature

We would love to hear your requests!
Please be aware that some features may not be applicable to all users.

- Open a GitHub [issue](https://github.com/cloudinary/cloudinary-angular-2/issues/new) describing the benefits (and possible drawbacks) of the requested feature

## Fixing a bug / Implementing a new feature

- Follow the instructions detailed in [Code contribution](#code-contribution)
- Open a new GitHub pull request
- Ensure the PR description clearly describes the bug / feature. Include the relevant issue number if applicable.
- Provide test code that covers the new code

## Code contribution

When contributing code, either to fix a bug or to implement a new feature, please follow these guidelines:

#### Fork the Project

Fork [project on Github](https://github.com/cloudinary/cloudinary-angular-2) and check out your copy.

```
git clone https://github.com/contributor/cloudinary_ng.git
cd cloudinary_ng
git remote add upstream https://github.com/cloudinary/cloudinary-angular-2.git
```

#### Create a Topic Branch

Make sure your fork is up-to-date and create a topic branch for your feature or bug fix.

```
git checkout master
git pull upstream master
git checkout -b my-feature-branch
```
#### Rebase

If you've been working on a change for a while, rebase with upstream/master.

```
git fetch upstream
git rebase upstream/master
git push origin my-feature-branch -f
```


#### Write Tests

Try to write a test that reproduces the problem you're trying to fix or describes a feature that you want to build.

We definitely appreciate pull requests that highlight or reproduce a problem, even without a fix.

#### Write Code

Implement your feature or bug fix.
Follow [Angular's style guide](https://angular.io/styleguide).

#### Write Documentation

Document any external behavior in the [README](README.md).

#### Commit Changes

Make sure git knows your name and email address:

```
git config --global user.name "Your Name"
git config --global user.email "contributor@example.com"
```

Writing good commit logs is important. A commit log should describe what changed and why.

```
git add ...
git commit
```


> Please squash your commits into a single commit when appropriate. This simplifies future cherry picks and keeps the git log clean.

#### Push

```
git push origin my-feature-branch
```

#### Make a Pull Request

Go to https://github.com/contributor/cloudinary_ng and select your feature branch. Click the 'Pull Request' button and fill out the form. 
Pull requests are usually reviewed within a few days.

Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.

#### Check on Your Pull Request

Go back to your pull request after a few minutes and see whether it passed the Travis-CI build. 
Everything should look green, otherwise fix issues and amend your commit as described above.

#### Be Patient

It's likely that your change will not be merged and that the nitpicky maintainers will ask you to do more, or fix seemingly benign problems. Hang on there!

#### Thank You

Please do know that we really appreciate and value your time and work, and that open source rocks!