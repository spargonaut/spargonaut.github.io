+++
draft = false
title = "Commit With the Why"
date = 2024-10-12T15:49:14-07:00
tags = ["git"]
slug = "Tell me WHY!" 
+++

# Commit with the "Why"

### FIXME - update the date of the post in the header info to be _after_ the Learn from history post.

There is a lot of documentation out there talking about how to craft a good commit message.
For Example, Here's just a few from a trivial search:
- [GitKraken](https://www.gitkraken.com/learn/git/best-practices/git-commit-message)
- [GitHub](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53)
- [The r/git subreddit](https://www.reddit.com/r/git/comments/f502nz/how_to_write_a_good_commit_message_focus_on/)
- [The Git-Pro book](https://git-scm.com/docs/git-commit#_discussion)

One of the common topics in each of those articles, that I _frequently_ see left out of commit
messages, is the "why"; **WHY** were the changes made?  The **WHAT** of the changes, what they are,
how they work, and what they do should be obvious from the changeset of the commit.

### The very important reason of **WHY** the change was made is best captured in the commit message.

When you capture the **WHY** a change was made in the commit message, you help others (and yourself!)
learn why something was done and why a codebase is factored the way it is.
