# sports-dec

## Guildeline

#### Branchs
- when you start a new task, create a new branch with task name, here is an example
```
git checkout main
git pull origin main
git checkout -b [task-name]
```

#### Commits
- commit is always important, so don't be afraid of it. commit frequently and small
- descriptive commits must have a description of what was done, like
```
git commit -m "[task-name] - [description whats was done]"
```

#### Code Review
- after finishing your task, create a PR so that another developer can analyze your code. `do not forget to inform who should be the reviewer, the type of label and the assignee, project and milestone if you have one`

#### Merge
- merge is important to test your implementation, follow these codes:
```
git checkout stage
git pull origin stage
git merge [task-name]
```
check if not have conflicts, if have, resolve them and push
```
git push origin stage
```


#### Pull Request
- the PR can be created only when finishing your task. 
```main <- [task-name]```


#### Deploy
- check if deploy is on github actions is auto deploy on (forge, aws amplify or similar), if have, take care when you accept a Pull Request.
