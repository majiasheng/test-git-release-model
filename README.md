# test-git-release-model
## Flows up till release 0.1:
1. Create master, develop branches
2. Create feature1 off of develop
3. Work on feature1, push changes to remote feature1 branch
4. Make pull request 1 (develop as base/target branch, feature1 branch as
  source branch)
5. Approve pull request
6. Checkout local develop branch, and pull origin
7. Create feature2 and repeat steps 3 to 6
8. Create release 0.1 branch, and write these steps
9. Commit and push changes to remote
10. Make pull request, master as base/target, release 0.1 as source
11. Approve pull request
12. Make pull request, develop as base/target, release 0.1 as source
13. Approve pull request
14. Checkout and pull develop

## Flows uptill release 0.2:
1. Created Alice and Bob feature
2. Commit and push changes in Alice and Bob features
3. Make pull request from Bob feature to develop
4. Approve pull request
5. Alice feature pulled develop branch before making pull request to
   develop
6. Approve Alice feature
7. Checkout and pull develop; create release 0.2
8. Write these steps
9. Commit and push changes to remote realse branch
10. Make pull request to master
11. Approve pull request
12. Make pull request to develop (release 0.2 as source)
13. Approve pull request


