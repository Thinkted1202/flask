# flask
flask 初版
# 建立軟連結
ln -s .env_development .env

# 建立migration
flask db init
flask db migrate
flask db upgrade

# 建立seed
flask seed run
