# イメージを取得
FROM nginx:1.25.0

# srcフォルダを/var/www/htmlにコピー
COPY src /var/www/html
# default.confを/etc/nginx/conf.dにコピー
COPY docker/default.conf /etc/nginx/conf.d

# Test config
#RUN nginx -t

# パッケージやPHPの拡張モジュールをインストールするコマンド　を実行
#RUN apt-get update && apt-get install -y \
#	git \
#	curl \
#	zip \
#	unzip \
 #   && docker-php-ext-install pdo_mysql

# 作業ディレクトリを/var/wwwに設定
#WORKDIR /var/www
