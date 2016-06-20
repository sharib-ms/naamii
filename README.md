# Nepal Applied Mathematics and Informatics Institute (NAAMII, नामी)
This repository serves as a means of a communication among the (potential) founding members, as a medium to contribute to our website, as a means to disseminate one's ideas and vision via blogs of our website.

## Submitting/Writing a blog
If you are not familiar with git or do not want to use github, just send us your article via email, and we can publish it for you.
But if you know git and have a github account, the preferred way to submit a blog article is to create a pull request (explained below) with the article in `posts` directory with a proper filename (date and title).
Please see other blog posts in that directory to know the header that you have to put in your file.


## Editing the website
You must first have a [github](https://github.com/) account if you want to propose some changes to the website.
If you want to notify us about errors in the website or enhancements you prefer, you can create an issue. [See here](https://help.github.com/articles/creating-an-issue/).

If you want to make edits on your own and want our website to be udpated with your edits, please create a pull request.
The general workflow for this would be as follows:

1. Fork this repository. [See here for step-wise instructions of properly forking a github repository.](https://help.github.com/articles/fork-a-repo/)
2. At this stage make sure that your local repository is synced with the upstream repository. [See here on how to do this](https://help.github.com/articles/syncing-a-fork/).
Now, create a new branch in your local repository where you will make the changes you want to make.
Once you have made the changes, push these local changes to your forked repository.
3. Initiate a pull request as explained [here](https://help.github.com/articles/using-pull-requests/)
4. If your pull request is merged, you can delete this branch from your local repo and from your forked repo using:
`git push origin --delete <branchName> # To delete the branch on github repo`
`git branch -d <branchName> # To delete the branch on your local repo`

## Building the website locally (offline)
### Requirements
1. [jekyll](https://jekyllrb.com/)
2. [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar)

