# stress-test-git
## How does git works


Git is a free and open source version control system, originally created by Linus Torvalds in 2005. Unlike older centralized version control systems such as SVN and CVS, Git is distributed: every developer has the full history of their code repository locally. This makes the initial clone of the repository slower, but subsequent operations such as commit, blame, diff, merge, and log dramatically faster.

Git also has excellent support for branching, merging, and rewriting repository history, which has lead to many innovative and powerful workflows and tools. Pull requests are one such popular tool that allow teams to collaborate on Git branches and efficiently review each others code. Git is the most widely used version control system in the world today and is considered the modern standard for software development.


1. Create the repository on Github.
2. Clone the repository to your local machine.
3. Create the development branch.
4. Create a feature branch from the development branch.
5. After making some changes, run  ```git add .``` in the terminal to move them to the staging area.
6. RUn ```git commit -m "message"``` to do a commit.
7. Run ```git push --set-upstream origin development``` to push your development branch to your repository on Github.
8. When the work on that branch is done, run ``git checkout development`` to move to the development branch.
9. Run ```git merge feature-branch``` to merge the branch development.
10. Run ```git push``` to push the updated development branch to your repository
11. Run ```git checkout main``` and then ```git merge development```
12. Run ```git push``` to push your updated main branch

Git also has excellent support for branching, merging, and rewriting repository history, which has lead to many innovative and powerful workflows and tools. Pull requests are one such popular tool that allow teams to collaborate on Git branches and efficiently review each others code. Git is the most widely used version control system in the world today and is considered the modern standard for software development.

1.pizza
2.banana
3.apple


![alt text](https://camo.githubusercontent.com/38f113b96a368dfb7f634d2f2da97e7b8c748042d2a284b97c3fad048bb3ff55/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f323733322f312a6d74736b3366515f4252656d466964686b656c3364412e706e67 "GIT")
 
