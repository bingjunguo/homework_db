# README

1.开发环境
* Ruby version: Ruby 2.3.1

* Rails version: Rails 5.1.4

* System dependencies: ubuntu

* Database creation: psql (PostgreSQL) 9.5.9


2.功能实现

* 主界面
  点击Blog进入功能区
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/home.png)
* 博客列表
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/article_list.png)
* 新建博客
  点击"New Article"，可新建博客；若放弃新建，可点击”Back”返回列表
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/new_article2.png)
* 编辑/更新博客
  点击"Edit"，可以编辑博客；若放弃编辑，可点击”Back”返回列表
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/edit_article.png)
  点击“Update Article”后，数据会更新
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/article_list2.png)
* 删除博客
  点击"Destroy"，会出现确认界面，防止误操作
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/confirm.png)
* 展示博客
  点击"Show"，会展示标题和全文，并提供编辑和返回列表功能
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/show.png)

3.值得注意
  如果新建的博客标题为空或者少于5个字符，则不能创建。
![image](https://github.com/bingjunguo/homework_db/blob/master/screenshots/cannot_new.png)