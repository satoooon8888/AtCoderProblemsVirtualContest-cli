# Overview
<a href="https://github.com/Tatamo/atcoder-cli">atcoder-cli</a>をAtCoderProblems VirtualContest用に改変したクローンです。

# Installation
```
npm install -g git+https://github.com/satoooon8888/AtCoderProblemsVirtualContest-cli
```

# Usage
accをaccpとして置き換えてください。accの各種コマンドが使えます。  
contest_idはAtCoderProblems-VirtualContestのURLの  
`https://kenkoooo.com/atcoder/#/contest/show/{id}`  
の部分で置き換えてください。  
通常のAtCoderのコンテストは利用できません。そのときは従来のaccを使ってください。

```
accp -h
accp new [contest_id]
accp s
```

# Changes
src/atcoder.tsをこのリポジトリのatcoder.tsに書き換えてビルドしました。ビルドしたものをcli.jsとして公開しています。  

# Thanks
atcoder-cliおよびonline-judge-toolsの開発者、貢献者様に深く感謝申し上げます。  
