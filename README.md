TEST
# test-git-release-model
Flows up till release 0.1:
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
