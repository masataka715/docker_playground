FROM centos:7

# centosにnginxのリポジトリを登録するため
COPY ./nginx/nginx.repo /etc/yum.repos.d/nginx.repo

RUN yum update -y && yum install -y nginx

# systemctlコマンドのため必要
CMD ["/sbin/init"]
# nginxサーバを起動
# CMD ["nginx", "-g", "daemon off;"]
