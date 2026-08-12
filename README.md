# test-repo
develop
feature

## branch ruleset
以下の条件の場合に，mainにdevelopがマージされてもブランチを消えないようにする

- default branchをdevelopにしておく

- Settings->Branches->Rulesets->Add branch ruleset
から，Branch rulesの Restrict deletionsにチェックを入れてルールを作成する
---
![alt text](image.png)
---
![alt text](image-2.png)
---

## settings
- Settings->Pull Requests
の，Automatically delete head branchesにはチェックを入れる(featブランチとかは消えたほうがよいだろうから)
---
![alt text](image-6.png)
---

## 2度目以降のマージ
- contributeのところを押せばよい
---
![alt text](image-1.png)
---
![alt text](image-3.png)
---
![alt text](image-7.png)
---