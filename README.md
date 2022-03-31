
# BANANA
---
## Git/Github workflow
### Starting a new feature/topic
1. Make sure main is up to date
```
git checkout main
git pull
```
2. Create new branch from main
```
git checkout -b yourname-feature
```
### Ready to submit
1. push your branch to Github
```
git push origin branchName
```
2. Create new pull request (Github)

![image](https://user-images.githubusercontent.com/49049363/159992767-b067db65-8331-493b-ba29-7b05e358a96e.png)

![image](https://user-images.githubusercontent.com/49049363/159993421-b3acf887-6574-4605-aee9-b56ce9ddb373.png)

![image](https://user-images.githubusercontent.com/49049363/159993520-daf20606-b3b9-4074-b4b3-8cfe668432ed.png)

3. Let the Git Lead know your changes are ready to be merged
4. The Git Lead will merge and post confirmation in chat. If there is a merge conflict, the Git Lead will talk to the relevant people to resolve.

### Other tips

1. Make sure the code works before committing
2. Limit the refactoring of code outside of your changes