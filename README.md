# flask
flask 初版
# 建立軟連結
ln -s .env_development .env

# 建立migration
flask db init<br/>
flask db migrate<br/>
flask db upgrade<br/>

# 建立seed
flask seed run<br/>
