# Audited Async Sample App

This app is just a sample for the gem [AuditedAsync](https://github.com/leonardofalk/audited_async.git).

To execute the application run:

```shell
bundle install
rails db:create db:migrate
rails server
```

There is only one model and it uses the async mode, [check it](./app/models/post.rb).
