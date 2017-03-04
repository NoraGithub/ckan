在盘符`/data1`，用[dpkg安装ckan](http://docs.ckan.org/en/latest/maintaining/installing/install-from-package.html)
帐号：ckan_default
密码：ckan_default

ckan.site_url = http://datasource.datavalue.cloud

vi `/etc/nginx/sites-available/ckan`

# nginx相关
server {
    # use 'listen 80 deferred;' for Linux
    # use 'listen 80 accept_filter=httpready;' for FreeBSD
    listen 80;

    server_name datavalue.cloud/datasource www.datavalue.cloud/datasource

#ckanext-googleanalytics


// reset
再买一台ecs做域名转发
root
2017@ckan
实例名称：ckan

datastore
http://docs.ckan.org/en/latest/maintaining/datastore.html

帐号：database_default
密码：database_default

admin帐号
geekhacker
2017geekhacker

#http://docs.ckan.org/en/latest/maintaining/getting-started.html#create-admin-user
#CKAN commands are executed using the paster command on the server that CKAN is installed on. Before running the paster commands below, you need to make sure that your virtualenv is activated and that you’re in your ckan source directory. For example:

. /usr/lib/ckan/default/bin/activate
cd /usr/lib/ckan/default/src/ckan

虚拟环境： . /usr/lib/ckan/default/bin/activate
目录：/usr/lib/ckan/default/src/ckan


安装datapusher


curl -X GET "http://data.datavalue.cloud/api/3/action/datastore_search?resourcde_id=_table_metadata"


安装dashboard_preview

虚拟环境安装
. /usr/lib/ckan/default/bin/activate

分享插件
https://github.com/yujiangshui/simple-share.js
