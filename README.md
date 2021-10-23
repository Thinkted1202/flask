# flask
flask 初版
# 建立軟連結
$ ln -s .env_development .env

# 建立migration
$ flask db init # 若沒有migration 再執行<br/>
$ flask db migrate # 若沒有migrate產生 再執行<br/>
$ flask db upgrade<br/>

# 建立seed
$ flask seed run<br/>
