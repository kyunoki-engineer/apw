FROM mysql:5.7

RUN touch /var/log/mysql/mysql.log #指定の場所にログを記録するファイルを作る

RUN apt-get update
RUN apt-get -y install locales-all

ENV LANG ja_JP.UTF-8
ENV LANGUAGE ja_JP:ja
ENV LC_ALL ja_JP.UTF-8

