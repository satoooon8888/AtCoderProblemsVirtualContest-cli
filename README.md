# Overview
<a href="https://github.com/Tatamo/atcoder-cli">atcoder-cli</a>をAtCoderProblems VirtualContest用に改変したクローンです。

# Installation
```
npm install git+https://github.com/satoooon8888/AtCoderProblemsVirtualContest-cli
```

# Usage
accpとして各種コマンドが使えます。  
contest_idはAtCoderProblems-VirtualContestのURLの  
`https://kenkoooo.com/atcoder/#/contest/show/{id}`  
の部分で置き換えてください。  

```
accp -h
accp new [contest_id]
accp s
```

# Changes
src/atcoder.tsをこのリポジトリのatcoder.tsに書き換えました。  

# Thanks
atcoder-cliおよびonline-judge-toolsの開発者、貢献者様に深く感謝申し上げます。