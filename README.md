<!---
{
  "depends_on": [],
  "author": "Tabea Röthemeyer",
  "first_used": "2025-04-02",
  "keywords": ["learning", "exercises", "github", "git"]
}
--->

# Git: Fork and Contribute on Github

## 1) Introduction
When developers want to share their projects, they use platforms designed specifically for collaboration, similar to social networks but specialized for code. GitHub is one prominent example that hosts and manages Git repositories. Besides hosting repositories, GitHub adds features like issues, project management, and pull requests.

To contribute code, developers commonly use a pullrequest, a structured suggestion to include code changes into another repository. A pullrequest specifies two branches, the one with the new changes and the one where the changes should be merged to. It also serves as an option to give feedback to code.

Since contributors often lack permissions to directly push branches to repositories they don't own, GitHub provides forks. A fork is your own personal copy of another repository. This enables you to freely make changes and then submit these changes back to the original repository via pull requests. This is possible as the target branch of a pull request can belong to another repository.
### 1.1) Further Readings and Other Sources
- [Where do I start with Git and GitHub](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git#where-do-i-start)
- [About Git and GitHub](https://docs.github.com/en/get-started/start-your-journey/about-github-and-git)
- [Reddit discussion: Why is GitHub so important](https://www.reddit.com/r/learnprogramming/comments/wg463w/why_is_github_so_important/)

## 2) Tasks
1. **Visit the VSCode Project on GitHub**: [VSCode on GitHub](https://github.com/microsoft/vscode) -> Take some time to browse the project and find out how GitHub lets you navigate different branches.
2. **Create your own project**: Upload a local Git repository to GitHub
3. **Create a Pullrequest in your own project**: Make sure that you have two different branches in your project and push them. Then, create a Pullrequest and inspect the changes. You can already merge it or ask someone else to review it.
4. **Protect your project**: Add branch protection rules so that only you (or maybe your friends as well) are allowed to push to your main branch.
5. **Contribute to this description**: Whilst this exercise is created with care, you might still find room for improvement. Fork this repository, make an edit that you would find useful, and create a Pullrequest. 

<details>
  <summary>Tip for Task 2</summary>
  There are multiple ways to accomplish this. GitHub already provides a lot of explanation. Just navigate to the "your repositories" View once logged in and click the new button. GitHub's UI will help you to either upload an existing project or create a new one.
   <summary>Tip for Task 5</summary>
  This is a very small example that highlights the general process of how you can contribute to other projects.
</details>

## 3) Questions
1. Why would you fork a project instead of contributing directly?
2. What different kinds of branch protection rules exist?
3. Look at the Pullrequest interfaces in GitHub and describe what kind of checks you can find - there are two categories of checks. 

## 4) Advice
While GitHub is commonly used, GitLab is also quite popular (and your university might provide you with a self-hosted option). When trying to understand GIt and GitHub, always think about what is Git and what is GitHub. Anything that can't be accomplished by doing `git <command> [whatever]` is most likely a GitHub feature. 

