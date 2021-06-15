# test-git-action
test for git actions


workflow reference:
https://docs.github.com/en/github/getting-started-with-github/quickstart/github-flow


- cd /Users/yuanyuan/Dropbox\ \(ASU\)/GitHubYuanyuan 
- ls
- git clone https://github.com/Yuanyuan2018/test-git-action.git
- cd test-git-action/
- git branch
- git remote -v
- git checkout -b reorganize
(Change the files…)
- (git status)
- git add -A
- git status
- git commit -m 'editing files & creating files"
- git push origin reorganize



Then, the GitHub repository updates to below:
￼![image](https://user-images.githubusercontent.com/43053656/122135552-97a84100-cdf5-11eb-94c6-9fb166c9f7f0.png)

Then, pull request:
￼![image](https://user-images.githubusercontent.com/43053656/122135676-cfaf8400-cdf5-11eb-86f5-e2be2661b542.png)

Then, merge if no issues
￼![image](https://user-images.githubusercontent.com/43053656/122135702-d807bf00-cdf5-11eb-8935-3154cb938d2f.png)

Click the ‘Merge pull request’, you will see:
￼![image](https://user-images.githubusercontent.com/43053656/122135721-df2ecd00-cdf5-11eb-864b-105e5400af95.png)





or the KWG version:

- clone a repository, edit on local, and push back
- cd /Users/yuanyuan/Dropbox\ \(ASU\)/GitHubYuanyuan/KWG/reorganize-work 
- ls
- clone https://github.com/KnowWhereGraph/kwg-seed-graph.git
- cd kwg-seed-graph/
- git branch
- git remote -v
- git checkout -b reorganize
- git status
- git add -A
- git status
- git commit -m 'reorganize KWG triplification files'
- git push origin reorganize
