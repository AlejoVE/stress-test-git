# stress-test-git

## Work flow

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
