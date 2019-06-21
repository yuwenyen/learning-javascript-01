# learning-javascript-01

テクノロジー（藤原）JavaScriptの練習 (1)

## Q1の回答「コメントを解除したことで、どう変化しましたか？」

ウェブサイトで"こんにちは"メッセージが出てきた

## Q2の回答「エラーの原因は何でしょうか？（調べてみましょう）」

値がないから

## Chromeデベロッパーツール：Consoleの実行結果

Navigated to http://127.0.0.1:5500/learning-javascript-01/index.html
main.js:4 Good morning.
index.html:18 おはよう！

## ターミナルの実行結果
Last login: Thu Jun 20 23:08:56 on ttys000
You have new mail.
yanyuwende-MacBook-Pro:~ yenyuwen$ cd ~/fujiwara
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ git clone git@github.com:yuwenyen/learning-javascript-01.git
Cloning into 'learning-javascript-01'...
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 0), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ code .
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ node node-main.js
-bash: node: command not found
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ node node-main.js
-bash: node: command not found
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ node node-main.js
-bash: node: command not found
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ vi ~/.bashrc
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ vi ~/.bash
.bash_history                .bash_sessions/
.bash_profile                .bashrc
.bash_profile-anaconda3.bak  
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ vi ~/.bash_profile
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ source ~/.bash_profile
-bash: .bashrc: No such file or directory
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ vi ~/.bash_profile
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ source ~/.bash_profile
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ node
-bash: node: command not found
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ echo "export PATH=$HOME/.nodebrew/current/bin:$PATH" >> ~/.bashrc
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ source ~/.bashrc
yanyuwende-MacBook-Pro:fujiwara yenyuwen$ node
Welcome to Node.js v12.4.0.
Type ".help" for more information.
> D
Thrown:
ReferenceError: D is not defined
> EXIT
Thrown:
ReferenceError: EXIT is not defined
> exit
Thrown:
ReferenceError: exit is not defined
> 
> quit
Thrown:
ReferenceError: quit is not defined
> 
Error: Cannot find module '/Users/yenyuwen/Documents/fujiwara/node-main.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}

yanyuwende-MacBook-Pro:fujiwara yenyuwen$ cd learning-javascript-01/
yanyuwende-MacBook-Pro:learning-javascript-01 yenyuwen$ node node-main.js
/Users/yenyuwen/Documents/fujiwara/learning-javascript-01/node-main.js:1
window.alert("Hello, Node.js!!");
^

ReferenceError: window is not defined
    at Object.<anonymous> (/Users/yenyuwen/Documents/fujiwara/learning-javascript-01/node-main.js:1:1)
    at Module._compile (internal/modules/cjs/loader.js:774:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
yanyuwende-MacBook-Pro:learning-javascript-01 yenyuwen$ 


