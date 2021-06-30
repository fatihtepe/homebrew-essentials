[How to Automate a Github Repo With a Line of Code on Linux](https://medium.com/mkdir-awesome/automate-creating-a-github-repo-with-a-line-of-code-on-linux-f21fb2aafebd)

[How to Automate a Github Repo With a Line of Code on MacOS](https://medium.com/mkdir-awesome/install-gitstart-with-homebrew-ec387f3ee189)

## Install Gitstart with Homebrew.

- Create a Github repo. [more on this article.](https://towardsdatascience.com/automate-creating-a-new-github-repository-with-gitstart-1ae961b99866)
- Create .gitignore if you provide a language.
- Add a license.txt depend on your choice.
- Create a new repo at GitHub.com.
- Create and add a README.md file with the repo name.
- Commit the repo with a message.
- Push the files to the remote repo

`Install`
```
brew tap shinokada/gitstart && brew install gitstart
```

`Then you can run:`

```
gitstart -d ./new_repo_name
```

`Find out more with`
```
 gitstart -h.
```

reference: [Shinichi Okada](https://blog.codewithshin.com/)
