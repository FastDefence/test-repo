# test-repo
develop
feature

## branch ruleset
以下の条件の場合に，mainにdevelopがマージされてもブランチを消えないようにする

- default branchをdevelopにしておく

Settings->Branches->Rulesets->Add branch ruleset
から，Branch rulesの Restrict deletionsにチェックを入れる
---
![alt text](image.png)
---
![alt text](image-2.png)
---

## settings
Settings->Pull Requests
の，Automatically delete head branchesにはチェックを入れない
---
![alt text](image-6.png)
---

## 2度目以降のマージ
---
![alt text](image-1.png)
---
![alt text](image-3.png)
---
![alt text](image-4.png)
---
![alt text](image-5.png)
---