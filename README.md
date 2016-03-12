`heroku auth:whoami`

`cd ~/src/github/`

`mkdir kanji-quizzer`

`cd kanji-quizzer`

`heroku create kanji-quizzer`

`git init`

`curl -d '{"name": "kanji-quizzer"}' -H X-GitHub-OTP:123456 -u davejagoda https://api.github.com/user/repos`

`git remote add origin git@github.com:davejagoda/kanji-quizzer.git`

`git add README.md`

`git commit -m 'add README.md'`

`git push -u origin master`
