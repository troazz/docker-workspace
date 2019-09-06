## PHP Docker Workspace
### This is docker workspace for multiple PHP version, I use 5.6 and 7.3 in here. There's MySQL and FakeSMPT containers too.

#### Requirements
1. Docker
2. Docker Compose
3. Git

#### How to use
1. Clone or download this repo `git clone git@github.com:troazz/php-docker-workspace.git`
2. Go to cloned folder `cd php-docker-workspace`
3. Copy environtment file `cp .env.example .env`
4. Set your environtment in .env file. You can turn specify port, restart behaviour, and mysql credential.
5. Create your vhost in this path *./etc/nginx/*, for example create this file *./etc/nginx/vhost.conf*. You can copy some vhost in this file *./etc/nginx/vhost.conf.example*
6. All set! Run docker `docker-compose up`
7. Wait until the process is done, and Voila!
8. Congratulation
