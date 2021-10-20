# Cloud-SPAN Contribution Guide
Hi there! Are you interested in contributing content to the Cloud-SPAN project? 

You're in the right place!

## Joining the Community
We welcome all contributions, big or small, and we'd love to welcome you into our community. 
We are open to people of all backgrounds with an interest in 'omics and/or cloud computing.

Please be aware of our [Code of Conduct]("https://github.com/Cloud-SPAN/CloudSPAN-handbook-bookdown/blob/master/CODE_OF_CONDUCT.md") which must be respected at all times during Cloud-SPAN events, courses and online interactions.

## Cloud-SPAN Course Structure
If you're thinking of making a contribution, it will be useful for you to understand how we structure our courses and repositories.

- Each course is divided into several "lessons". Each lesson contains several "episodes".
- Each lesson gets its own repository, which is named using the format **course-name** + **number** + **lesson-name**. For example, the first lesson of our Genomics course (*Project Management for Cloud Genomics*) is named **genomics02-proj-mngt-cloud-genomics**.
    - Be aware that repo-01 of each course is reserved for the course introduction/overview.
    - This means that the first lesson of each course is labelled as 02, the second as 03 and so on.
- Each lesson has a homepage which contains introductory information and an overview of the topics included.This page is stored under the name **"index.md"**.
- Episodes are stored as markdown files inside the relevant lesson repository under a folder named **"_episodes"**.
    - These episodes are numbered conventionally such that episode-01 corresponds to the first episode of that lesson, episode-02 to the second and so on.

## Contributing via GitHub 

[Git](https://git-scm.com) is a really useful tool for version control. 
[GitHub](https://github.com) sits on top of Git and supports collaborative and distributed working.

We know that it can be daunting to start using Git and GitHub if you haven't worked with them in the past, but our maintainers are here to help you figure out any of the jargon or confusing instructions you encounter! :heart:

In order to contribute via GitHub, you'll need to set up a free account and sign in.
Here are some [instructions](https://help.github.com/articles/signing-up-for-a-new-github-account/) to help you get going.
Remember that you can ask us any questions you need to along the way.

## Writing in Markdown

GitHub has a helpful page on [getting started with writing and formatting on GitHub](https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github).

Most of the writing that you'll do will be in [Markdown](https://daringfireball.net/projects/markdown).
You can think of Markdown as a few little symbols around your text that will allow GitHub to render the text with a little bit of formatting.
For example, you could write words as **bold** (`**bold**`), or in _italics_ (`_italics_`), or as a [link](https://youtu.be/dQw4w9WgXcQ) (`[link](https://youtu.be/dQw4w9WgXcQ)`) to another webpage.

Also, when writing in Markdown please start each new sentence on a new line.
Having each sentence on a new line will make no difference to how the text is displayed- there will still be paragraphs- but it makes the [diffs produced during the pull request](https://help.github.com/en/articles/about-comparing-branches-in-pull-requests) review easier to read! :sparkles:

## Share your thoughts
Whether you have something to contribute, a question to ask or a suggestion to make, the first thing you should do is open an issue. 
This keeps us up to date with any changes you're thinking about and helps prevent unnecessary conflict between versions.

Please try and open your issue in the repository associated with the lesson or episode you want to contribute to. 
If your issue spans several lessons, or is more general, then just use your judgement. 
Our maintainers will sort you out if you get it wrong!

You should also check existing open issues to make sure you're not duplicating someone else's work.

## Submitting a pull request
The following steps are a guide to help you contribute in a way that will be easy for everyone to review and accept with ease :sunglasses:.

### 1. Comment on an existing issue or open a new issue referencing your addition

This allows other members of the Cloud-SPAN team to confirm that you aren't overlapping with work that's currently underway and that everyone is on the same page with the goal of the work you're going to carry out.

[This blog](https://www.igvita.com/2011/12/19/dont-push-your-pull-requests/) is a nice explanation of why putting this work in upfront is so useful to everyone involved.

### 2. [Fork](https://help.github.com/articles/fork-a-repo) the relevant repo

This is now your own unique copy of that repo.
Changes here won't affect anyone else's work, so it's a safe space to explore edits to the code!

Make sure to [keep your fork up to date](https://help.github.com/articles/syncing-a-fork) with the master repository, otherwise, you can end up with lots of dreaded [merge conflicts](https://help.github.com/articles/about-merge-conflicts).
If you prefer working in the browser, [these instructions](https://github.com/KirstieJane/STEMMRoleModels/wiki/Syncing-your-fork-to-the-original-repository-via-the-browser) describe how to sync your fork to the original repository via GitHub.

### 3. Make the changes you've discussed

Try to keep the changes focused.
If you submit a large amount of work all in one go it will be much more work for whoever is reviewing your pull request.
Help them help you. :wink:

While making your changes, commit often and write good, detailed commit messages.
[This blog](https://chris.beams.io/posts/git-commit/) explains how to write a good Git commit message and why it matters.
It is also perfectly fine to have a lot of commits - including ones that break code.
A good rule of thumb is to push up to GitHub when you _do_ have passing tests then the continuous integration (CI) has a good chance of passing everything. ????

If you feel tempted to "branch out" then please make a [new branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository) and a new issue to go with it. [This blog](https://nvie.com/posts/a-successful-git-branching-model/) details the different Git branching models.

Please do not re-write history!
That is, please do not use the [rebase](https://help.github.com/en/articles/about-git-rebase) command to edit previous commit messages, combine multiple commits into one, or delete or revert commits that are no longer necessary.

Are you new to Git and GitHub or just want a detailed guide on getting started with version control? Check out the [Version Control chapter](https://the-turing-way.netlify.com/version_control/version_control.html) in _The Turing Way_ Book!

### 4. Submit a [pull request](https://help.github.com/articles/creating-a-pull-request)

We encourage you to open a pull request as early in your contributing process as possible.
This allows everyone to see what is currently being worked on.
It also provides you, the contributor, feedback in real-time from both the community and the continuous integration as you make commits (which will help prevent stuff from breaking).

When you are ready to submit a pull request, you will be asked to provide a title and description. The clearer your title and description are, the faster your request will be approved.
- Describe the problem you're trying to fix in the pull request, reference any related issue and use fixes/close to automatically close them, if pertinent.
- Include a list of changes proposed in the pull request.

If you have opened the pull request early and know that its contents are not ready for review or to be merged, add "[WIP]" at the start of the pull request title, which stands for "Work in Progress".
When you are happy with it and are happy for it to be merged into the main repository, change the "[WIP]" in the title of the pull request to "[Ready for review]".

A member of Cloud-SPAN team will then review your changes to confirm that they can be merged into the main repository.
A [review](https://help.github.com/articles/about-pull-request-reviews) will probably consist of a few questions to help clarify the work you've done.
Keep an eye on your GitHub notifications and be prepared to join in that conversation.

You can update your [fork](https://help.github.com/articles/fork-a-repo) of the repo and the pull request will automatically update with those changes.
You don't need to submit a new pull request when you make a change in response to a review.

GitHub has a [nice introduction](https://guides.github.com/introduction/flow) to the pull request workflow, but please get in touch if you have any questions :balloon:.

## Recognising Contributions

We welcome and recognise all kinds of contributions, from reporting/fixing bugs, to developing documentation, asking questions, answering questions, or suggesting new examples.
Cloud-SPAN follows the [all-contributors](https://github.com/kentcdodds/all-contributors#emoji-key) specifications.
The all-contributors bot usage is described [here](https://allcontributors.org/docs/en/bot/usage).

The Cloud-SPAN project is split across multiple repos, so we use **this repo** (Cloud-SPAN-handbook) as our community hub.
Regardless of which repo/lesson you have contributed to, we invite you to add yourself as a contributor here.
To add yourself or someone else as a contributor, comment on the 'add contributor' issue in this repo with the following:

```
@all-contributors please add <username> for <contributions>
```

You can see the [Emoji Key (Contribution Types Reference)](https://allcontributors.org/docs/en/emoji-key) for a list of valid `<contribution>` types.
The bot will then create a Pull Request to add the contributor and reply with the pull request details.

---

These guidelines have been adapted from the [Contributing Guidelines](https://raw.githubusercontent.com/alan-turing-institute/the-turing-way/master/CONTRIBUTING.md) of the [Turing Way](https://github.com/alan-turing-institute/the-turing-way)