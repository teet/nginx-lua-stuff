# Openresty (Nginx + Lua + much more)




This is a collection of nginx/lua scripts, that I'd like to keep track on. It uses git subtrees, so you'll get all the sources.
Nginx + Lua seems like a killer combination, and could provide a better foundation for some apps, than e.g Node.js or some other.



## Posts / Presentations:
  - http://3scale.github.io/2013/04/18/accelerate-your-mobile-api-with-nginx-and-lua/
  - http://www.slideshare.net/mizzy/inside-sqales-backend-at-yapcasia-tokyo-2012 (!!!)
  - http://www.textrazor.com/blog/2013/03/scaling-textrazor-in-the-cloud-with-nginx-and-lua.html
  - http://3scale.github.com/2013/01/09/augment-your-api-without-touching-it/
  - http://blog.cloudflare.com/pushing-nginx-to-its-limit-with-lua
  - http://seatgeek.com/blog/dev/oauth-support-for-nginx-with-lua
  - http://mikeferrier.com/2011/05/14/my-beautiful-dark-twisted-reverse-proxy-LRU-cache/ (!!!)
  - http://www.nginx-discovery.com/2011/03/day-41-setting-up-ngxopenresty-was.html
  - http://www.londonlua.org/scripting_nginx_with_lua/slides.html?full
  - http://ntcn.net/blog/?p=4469 (High Performance Caching with Nginx, Redis & PHP)


## OpenResty:

  - http://openresty.org/
  - http://openresty.org/download/agentzh-nginx-tutorials-enuk.html (!!!)
  - https://github.com/agentzh/ngx_openresty
  - http://qa.openresty.org/
  - https://github.com/kindy/lj-web

  - http://agentzh.org/misc/slides/ngx-openresty-ecosystem/#1
  - http://agentzh.org/misc/slides/ngx-openresty-ecosystem.pdf

  - http://agentzh.org/misc/slides/libdrizzle-lua-nginx/#2
  - http://agentzh.org/misc/slides/libdrizzle-lua-nginx.pdf

  - http://agentzh.org/misc/slides/perl-lz-apps.pdf
  - http://agentzh.org/misc/slides/nginx-conf-scripting/
  - http://agentzh.org/misc/slides/nginx-conf-scripting.pdf
  - http://agentzh.org/misc/slides/nginx-state-of-the-art/
  - http://agentzh.org/misc/slides/taobao-fe-vdomwebkit.pdf


Examples for OpenResty:

  - https://github.com/37signals/intermission
  - https://github.com/samalba/hipache-nginx
  - https://github.com/shrikeh/csrf-nginx-redis-lua
  - https://github.com/irr/stock-labs
  - https://github.com/agentzh/mysql-driver-benchmark (with MySQL)
  - https://gist.github.com/justincormack/948423 (proxy to AWS, with crypto stuff)
  - https://github.com/torhve/Amatyr (Postgres + Webapp)


## Nginx general:
  - [Настраиваем NGINX для мультиязычных сайтов](http://habrahabr.ru/company/ruvpn/blog/183060/)


<!-- PROJECTS_LIST_START -->
    37signals/intermission:
      intermission helps you perform zero down time application maintenance
       3 commits, last change: 2012-12-10 11:12:53, 134 stars, 6 forks

    agentzh/array-var-nginx-module:
      Add support for array variables to nginx config files
       41 commits, last change: 2012-06-01 19:25:08, 16 stars, 1 forks

    agentzh/echo-nginx-module:
      An Nginx module for bringing the power of "echo", "sleep", "time" and more to Nginx's config file
       368 commits, last change: 2013-06-28 11:38:36, 126 stars, 35 forks

    agentzh/encrypted-session-nginx-module:
      encrypt and decrypt nginx variable values
       53 commits, last change: 2013-06-11 12:20:29, 46 stars, 8 forks

    agentzh/headers-more-nginx-module:
      Set, add, and clear arbitrary output headers
       160 commits, last change: 2013-06-13 11:07:32, 149 stars, 16 forks

    agentzh/lua-resty-memcached:
      Lua memcached client driver for the ngx_lua based on the cosocket API
       106 commits, last change: 2013-04-11 11:31:00, 35 stars, 8 forks

    agentzh/lua-resty-mysql:
      Nonblocking Lua MySQL driver library for ngx_lua
       88 commits, last change: 2013-04-25 23:06:32, 43 stars, 19 forks

    agentzh/lua-resty-redis:
      Lua redis client driver for the ngx_lua based on the cosocket API
       97 commits, last change: 2013-02-08 11:28:14, 97 stars, 22 forks

    agentzh/lua-resty-string:
      String utilities and common hash functions for ngx_lua and LuaJIT
       39 commits, last change: 2012-11-20 11:35:44, 19 stars, 10 forks

    agentzh/lua-resty-upload:
      Streaming reader and parser for http file uploading based on ngx_lua cosocket
       45 commits, last change: 2013-03-24 22:27:20, 36 stars, 6 forks

    agentzh/memc-nginx-module:
      An extended version of the standard memcached module that supports set, add, delete, and many more memcached commands.
       199 commits, last change: 2013-01-30 23:08:46, 90 stars, 20 forks

    agentzh/nginx-systemtap-toolkit:
      Real-time analyzing and diagnosing tools for Nginx based on SystemTap
       159 commits, last change: 2013-07-01 14:02:43, 87 stars, 28 forks

    agentzh/ngx_openresty:
      Turning Nginx into a Full-fledged Web App Server
       636 commits, last change: 2013-07-09 18:17:51, 371 stars, 45 forks

    agentzh/rds-csv-nginx-module:
      Nginx output filter module to convert Resty-DBD-Streams (RDS) to Comma-Separated Values (CSV)
       32 commits, last change: 2012-09-17 12:12:20, 7 stars, 1 forks

    agentzh/rds-json-nginx-module:
      An nginx output filter that formats Resty DBD Streams generated by ngx_drizzle and others to JSON
       172 commits, last change: 2012-09-17 12:10:28, 72 stars, 7 forks

    agentzh/redis2-nginx-module:
      Nginx upstream module for the Redis 2.0 protocol
       129 commits, last change: 2013-04-08 22:53:20, 239 stars, 28 forks

    agentzh/replace-filter-nginx-module:
      Streaming regular expression replacement in response bodies
       72 commits, last change: 2013-06-30 22:45:37, 13 stars, 4 forks

    agentzh/srcache-nginx-module:
      Transparent subrequest-based caching layout for arbitrary nginx locations.
       253 commits, last change: 2013-06-11 16:48:36, 66 stars, 8 forks

    agentzh/test-nginx:
      Perl testing facilities for Nginx C module development
       278 commits, last change: 2013-06-10 13:14:02, 36 stars, 10 forks

    appwilldev/moochine-demo:
      OpenResty(ngx_lua, http://openresty.org )+Moochine 完整实例
       89 commits, last change: 2013-06-27 07:53:38, 25 stars, 4 forks

    appwilldev/moochine:
      MOOCHINE - A simple and lightweight web framework based on OpenResty(ngx_lua, http://openresty.org).
       171 commits, last change: 2013-03-26 19:19:40, 80 stars, 8 forks

    bakins/lua-resty-riak:
      Lua riak protocol buffer client driver for the ngx_lua based on the cosocket API
       199 commits, last change: 2013-06-20 07:33:11, 7 stars, 1 forks

    bakins/stardust:
      Simple OpenResty web framework
       86 commits, last change: 2013-07-09 05:18:08, 0 stars, 0 forks

    benagricola/openresty-squiz-util:
      A Squiz Lua module for OpenResty to provide an error-tolerant set of tools allowing for the succinct implementation of logic directly in the webserver configuration file.
       9 commits, last change: 2013-02-07 06:28:31, 0 stars, 0 forks

    bsm/fakengx:
      Library for testing Lua scripts embedded into Nginx
       24 commits, last change: 2013-03-06 00:59:51, 3 stars, 0 forks

    chaoslawful/drizzle-nginx-module:
      an nginx upstream module that talks to mysql and drizzle by libdrizzle
       400 commits, last change: 2013-03-27 12:47:35, 145 stars, 13 forks

    chaoslawful/lua-nginx-module:
      Embed the Power of Lua into NginX
       1000+ commits, last change: 2013-07-09 17:00:01, 693 stars, 140 forks

    cloudaice/redis-restful:
      a restful API for redis and base on openresty
       80 commits, last change: 2013-06-29 03:04:42, 2 stars, 1 forks

    cloudflare/lua-nginx-cache-module:
      lua-nginx bindings to inspect upstream cache meta-data
       9 commits, last change: 2012-08-14 20:43:23, 5 stars, 1 forks

    desbouis/nginx-redis-proxy:
      Nginx as reverse proxy using redis as cache engine
       44 commits, last change: 2012-03-21 16:49:42, 22 stars, 2 forks

    garethr/nginx-json-proxy:
      An experiment with openresty, lua and nginx
       2 commits, last change: 2013-07-02 12:26:41, 0 stars, 1 forks

    jtarchie/sinatra-openresty:
      Sinatra ported to OpenResty framework.
       12 commits, last change: 2013-06-30 13:31:54, 0 stars, 0 forks

    leafo/moonrocks-site:
      a website for submitting and hosting lua rocks
       112 commits, last change: 2013-06-16 22:18:17, 12 stars, 1 forks

    medcl/lua-resty-weedfs:
      weefs,lua,nginx and file post processing with ffmpeg and graphicsmagick
       7 commits, last change: 2013-04-11 02:17:27, 5 stars, 2 forks

    observing/balancerbattle:
      WebSocket loadbalancer battle
       53 commits, last change: 2013-05-24 01:27:01, 232 stars, 14 forks

    pgaertig/nginx-big-upload:
      Resumable and reliable file uploads of any size. Nginx extension written in Lua.
       22 commits, last change: 2013-05-27 14:35:21, 22 stars, 3 forks

    pintsized/ledge:
      A Lua module for OpenResty, providing scriptable HTTP cache (edge) functionality for Nginx.
       453 commits, last change: 2013-05-31 06:06:27, 46 stars, 7 forks

    samalba/hipache-nginx:
      Dynamic HTTP routing with Nginx and Redis (reimplements Hipache with Nginx using the Lua module)
       7 commits, last change: 2013-03-21 18:38:22, 52 stars, 7 forks

    solso/api-aggregator:
      Aggregate REST API calls easily on a sandboxed Nginx+Lua env
       14 commits, last change: 2013-04-17 01:39:02, 29 stars, 0 forks

    thattommyhall/nginx-lua-examples:

       7 commits, last change: 2013-03-19 12:09:06, 2 stars, 2 forks

    thattommyhall/nginx-lua-examples:

       7 commits, last change: 2013-03-19 12:09:06, 2 stars, 2 forks

    torhve/Amatyr:
      Amateur weather graphs using d3 js, watch js, rivets js, lua, postgresql, nginx
       157 commits, last change: 2013-06-04 06:15:43, 19 stars, 4 forks

    torhve/LuaWeb:
      A very simple blog enging using opreresty, nginx, lua, markdown, git and redis
       37 commits, last change: 2013-05-17 05:14:50, 24 stars, 4 forks

    torhve/Nyfyk:
      HTML5 RSS Reader app. SQLite3+newsbeuter+openresty-backend
       38 commits, last change: 2013-04-07 02:48:31, 0 stars, 0 forks

    wstucco/ssga.lua:
      Server Side Google Analytics in LUA
       7 commits, last change: 2013-01-28 08:55:07, 1 stars, 0 forks

    xinqiyang/yagamiko:
      yagamiko is a api server project implementation by lua  nginx ( openresty) .
       7 commits, last change: 2013-06-17 06:38:44, 0 stars, 0 forks
<!-- PROJECTS_LIST_END -->
