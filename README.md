# Free TON DevOps Governance Repository

## How to open Pull Request

1. Fork SG repository https://github.com/freeton-org/devops to your account
![image](https://user-images.githubusercontent.com/15122233/114208472-30d65980-9966-11eb-800f-bf1a4425e4ca.png)

2. Clone the fork and add your repo's commits to submission directory
```sh
git clone https://github.com/<YOUR_NAME>/devops.git
cd devops/
git subtree add --prefix <PROPOSAL_NUM>/<SUBMISSION_NUM>/<REPO_NAME> https://github.com/<REPO_USER>/<REPO_NAME>.git contest
git push
```

+ <YOUR_NAME> - your GitHub account name
+ <PROPOSAL_NUM> - proposal number
+ <SUBMISSION_NUM> - submission number
+ <REPO_USER> - your solution repo owner
+ <REPO_NAME> - your solution name

3. Open pull request into SG repo from your fork
![image](https://user-images.githubusercontent.com/15122233/114210462-7ac03f00-9968-11eb-980e-2ac4bafbd5d5.png)
