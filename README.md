# blog.okochang.com

Middlemanを使って作ってみたブログサイト

# 使っているもの

- Middleman
  - http://middlemanapp.com/jp/
- middleman-blog-bootstrap-template
  - https://github.com/biblichor/middleman-blog-bootstrap-template

# 記事の追加

````
$ bundle exec middleman article TITLE
````

# 最新版をS3にアップ

````
$ bundle exec middleman build
$ bundle exec middleman s3_sync 
````
