# Nepal Applied Mathematics and Informatics Institute (NAAMII, नामी)
This repository serves as a means of a communication among the (potential) founding members, as a medium to contribute to our website, as a means to disseminate one's ideas and vision via blogs of our website.

## Submitting/Writing a blog
If you are not familiar with git or do not want to use github, just send us your article via email, and we can publish it for you.
But if you know git and have a github account, the preferred way to submit a blog article is to create a pull request (explained below) with the article in `posts` directory with a proper filename (date and title).
Please see other blog posts in that directory to know the header that you have to put in your file.


## Editing the website

If you do not want to edit/update the website on your own but only want to notify us about the errors in the website or enhancements you prefer, just create a [github](https://github.com/) account and then create an issue. [See here](https://help.github.com/articles/creating-an-issue/).

If you want to request an edit by being so awesome that you yourself make the necessary changes locally in your computer and then propose us to merge those changes on our repository, then:

### Requirements
1. An [github](https://github.com/) account.
2. [jekyll](https://jekyllrb.com/)
3. [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar)

Once you have the requirements, fork this repository: [step-wise instructions of properly forking a github repository.](https://help.github.com/articles/fork-a-repo/)
Clone your forked repository to your local computer and check that you have properly installed the requirements by building the website as follows:
`jekyll build && jekyll serve`

Now, check if you can properly browse the website locally with this local address: `http://localhost:4000/naamii/`

Once you get this far, now it's time to make your edits and creating a pull request to have those edits merged with our repository.

[VERIFY that whatever changes you have made is built error-free by jekyll and looks fine locally before creating the pull request!]

General workflow:
1. Make sure that your local repository is synced with the upstream repository. [See here on how to do this](https://help.github.com/articles/syncing-a-fork/).
2. Create a new branch in your local repository where you will make the changes you want to make.
3. VERIFY that the changes you make build without error and that you can see the changes you want at `http://localhost:4000/naamii/`
4. Commit the changes in your local branch.
3. Initiate a pull request as explained [here](https://help.github.com/articles/using-pull-requests/)
4. If your pull request is merged, you can delete this branch from your local repo and from your forked repo using:
`git push origin --delete <branchName> # To delete the branch on github repo`
`git branch -d <branchName> # To delete the branch on your local repo`

## Building the website locally (offline)

