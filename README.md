# Overview
<a href="https://github.com/Tatamo/atcoder-cli">atcoder-cli</a>のAtCoderProblems-VirtualContest用に改変したクローンです。

# Installation
`npm install git+https://github.com/satoooon8888/AtCoderProblemsContest-cli.git`

# Usage
accpとして各種コマンドが使えます。  
contest_idはAtCoderProblems-VirtualContestのURLの  
https://kenkoooo.com/atcoder/#/contest/show/{id}  
の部分として置き換えてください。  

```shell
accp new [contest_id]
accp s
```

# Changes
src/atcoder.tsをこのリポジトリのatcoder.tsのように書き換えました。
package.jsonに