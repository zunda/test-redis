# test-redis
A small program to stress memory on Heroku Redis

```
$ bundle install --path=vendor/path
$ bundle exec ./bin/stress `heroku config:get REDIS_URL`
  :
...vendor/path/ruby/2.3.0/gems/redis-3.3.1/lib/redis/client.rb:121:in `call': OOM command not allowed when used memory > 'maxmemory'. (Redis::CommandError)
  :
```
