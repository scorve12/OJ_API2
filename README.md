# OnlineJudge 2.0

[![Python](https://img.shields.io/badge/python-3.8.0-blue.svg?style=flat-square)](https://www.python.org/downloads/release/python-362/)
[![Django](https://img.shields.io/badge/django-3.2.9-blue.svg?style=flat-square)](https://www.djangoproject.com/)
[![Django Rest Framework](https://img.shields.io/badge/django_rest_framework-3.12.0-blue.svg?style=flat-square)](http://www.django-rest-framework.org/)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudge.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudge)

> #### An onlinejudge system based on Python and Vue. [Demo](https://qduoj.com)

[中文文档](README-CN.md)

## Overview

+ Based on Docker; One-click deployment
+ Separated backend and frontend; Modular programming; Micro service
+ ACM/OI rule support; realtime/non-realtime rank support
+ Amazing charting and visualization
+ Template-problem support
+ More reasonable permission control
+ Multi-language support: `C`, `C++`, `Java`, `Python2`, `Python3`
+ Markdown & MathJax support
+ Contest participants IP limit(CIDR)

Main modules are available below:

+ Backend(Django): [https://github.com/QingdaoU/OnlineJudge](https://github.com/QingdaoU/OnlineJudge)
+ Frontend(Vue): [https://github.com/QingdaoU/OnlineJudgeFE](https://github.com/QingdaoU/OnlineJudgeFE)
+ Judger Sandbox(Seccomp): [https://github.com/QingdaoU/Judger](https://github.com/QingdaoU/Judger)
+ JudgeServer(A wrapper for Judger): [https://github.com/QingdaoU/JudgeServer](https://github.com/QingdaoU/JudgeServer)

## Installation

Follow me:  [https://github.com/QingdaoU/OnlineJudgeDeploy/tree/2.0](https://github.com/QingdaoU/OnlineJudgeDeploy/tree/2.0)

## Documents

[http://opensource.qduoj.com/](http://opensource.qduoj.com/)

## Screenshots

### Frontend:

![problem-list](https://user-images.githubusercontent.com/20637881/33372506-402022e4-d539-11e7-8e64-6656f8ceb75a.png)

![problem-details](https://user-images.githubusercontent.com/20637881/33372507-4061a782-d539-11e7-8835-076ddae6b529.png)

![statistic-info](https://user-images.githubusercontent.com/20637881/33372508-40a0c6ce-d539-11e7-8d5e-024541b76750.png)

![contest-list](https://user-images.githubusercontent.com/20637881/33372509-40d880dc-d539-11e7-9eba-1f08dcb6b9a0.png)

You can control the menu and chart status in rankings.

![acm-rankings](https://user-images.githubusercontent.com/20637881/33372510-41117f68-d539-11e7-9947-70e60bad3cf2.png)

![oi-rankings](https://user-images.githubusercontent.com/20637881/33372511-41d406fa-d539-11e7-9947-7a2a088785b0.png)

![status](https://user-images.githubusercontent.com/20637881/33372512-420ba240-d539-11e7-8645-594cac4a0b78.png)

![status-details](https://user-images.githubusercontent.com/20637881/33365523-787bd0ea-d523-11e7-953f-dacbf7a506df.png)

![user-home](https://user-images.githubusercontent.com/20637881/33365521-7842d808-d523-11e7-84c1-2e2aa0079f32.png)

### Admin: 

![admin-users](https://user-images.githubusercontent.com/20637881/33372516-42c34fda-d539-11e7-9f4e-5109477f83be.png)

![judge-server](https://user-images.githubusercontent.com/20637881/33372517-42faef9e-d539-11e7-9f17-df9be3583900.png)

![create-problem](https://user-images.githubusercontent.com/20637881/33372513-42472162-d539-11e7-8659-5497bf52dbea.png)

![create-contest](https://user-images.githubusercontent.com/20637881/33372514-428ab922-d539-11e7-8f68-da55dedf3ad3.png)

## Browser Support

Modern browsers(chrome, firefox) and Internet Explorer 10+.

## Thanks

+ I'd appreciate a star if you find this helpful.
+ Thanks to everyone that contributes to this project.
+ Special thanks to [heb1c](https://github.com/hebicheng), who has given us a lot of suggestions.

## License

[MIT](http://opensource.org/licenses/MIT)

```
OnlineJudge
├─ .dockerignore
├─ .flake8
├─ .git
│  ├─ config
│  ├─ description
│  ├─ FETCH_HEAD
│  ├─ HEAD
│  ├─ hooks
│  │  ├─ applypatch-msg.sample
│  │  ├─ commit-msg.sample
│  │  ├─ fsmonitor-watchman.sample
│  │  ├─ post-update.sample
│  │  ├─ pre-applypatch.sample
│  │  ├─ pre-commit.sample
│  │  ├─ pre-merge-commit.sample
│  │  ├─ pre-push.sample
│  │  ├─ pre-rebase.sample
│  │  ├─ pre-receive.sample
│  │  ├─ prepare-commit-msg.sample
│  │  ├─ push-to-checkout.sample
│  │  ├─ sendemail-validate.sample
│  │  └─ update.sample
│  ├─ index
│  ├─ info
│  │  └─ exclude
│  ├─ logs
│  │  ├─ HEAD
│  │  └─ refs
│  │     ├─ heads
│  │     │  └─ master
│  │     └─ remotes
│  │        └─ origin
│  │           └─ HEAD
│  ├─ objects
│  │  ├─ info
│  │  └─ pack
│  │     ├─ pack-a796902ac4076dc1d805174990ce602392e5f83b.idx
│  │     ├─ pack-a796902ac4076dc1d805174990ce602392e5f83b.pack
│  │     └─ pack-a796902ac4076dc1d805174990ce602392e5f83b.rev
│  ├─ packed-refs
│  └─ refs
│     ├─ heads
│     │  └─ master
│     ├─ remotes
│     │  └─ origin
│     │     └─ HEAD
│     └─ tags
├─ .github
│  ├─ issue_template.md
│  └─ workflows
│     └─ release.yml
├─ .gitignore
├─ .travis.yml
├─ account
│  ├─ decorators.py
│  ├─ middleware.py
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_auto_20170209_1028.py
│  │  ├─ 0003_userprofile_total_score.py
│  │  ├─ 0005_auto_20170830_1154.py
│  │  ├─ 0006_user_session_keys.py
│  │  ├─ 0008_auto_20171011_1214.py
│  │  ├─ 0009_auto_20171125_1514.py
│  │  ├─ 0010_auto_20180501_0436.py
│  │  ├─ 0011_auto_20180501_0456.py
│  │  ├─ 0012_userprofile_language.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ serializers.py
│  ├─ tasks.py
│  ├─ templates
│  ├─ tests.py
│  ├─ urls
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  ├─ views
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  └─ __init__.py
├─ announcement
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_auto_20171011_1214.py
│  │  ├─ 0003_auto_20180501_0436.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ serializers.py
│  ├─ tests.py
│  ├─ urls
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  ├─ views
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  └─ __init__.py
├─ conf
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_auto_20171011_1214.py
│  │  ├─ 0003_judgeserver_is_disabled.py
│  │  ├─ 0004_auto_20180501_0436.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ serializers.py
│  ├─ tests.py
│  ├─ urls
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  ├─ views.py
│  └─ __init__.py
├─ contest
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_auto_20170209_0845.py
│  │  ├─ 0003_auto_20170217_0820.py
│  │  ├─ 0004_auto_20170717_1324.py
│  │  ├─ 0005_auto_20170823_0918.py
│  │  ├─ 0006_auto_20171011_1214.py
│  │  ├─ 0007_contestannouncement_visible.py
│  │  ├─ 0008_contest_allowed_ip_ranges.py
│  │  ├─ 0009_auto_20180501_0436.py
│  │  ├─ 0010_auto_20190326_0201.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ serializers.py
│  ├─ tests.py
│  ├─ urls
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  ├─ views
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  └─ __init__.py
├─ data
│  └─ public
│     └─ website
│        └─ favicon.ico
├─ deploy
│  ├─ entrypoint.sh
│  ├─ health_check.py
│  ├─ nginx
│  │  ├─ api_proxy.conf
│  │  ├─ https_redirect.conf
│  │  ├─ locations.conf
│  │  └─ nginx.conf
│  ├─ requirements.txt
│  ├─ supervisord.conf
│  └─ test_case_rsync
│     ├─ Dockerfile
│     ├─ rsyncd.conf
│     └─ run.sh
├─ Dockerfile
├─ docs
│  └─ data.json
├─ fps
│  ├─ fps.xml
│  ├─ parser.py
│  └─ __init__.py
├─ init_db.sh
├─ judge
│  ├─ dispatcher.py
│  ├─ languages.py
│  ├─ tasks.py
│  └─ __init__.py
├─ LICENSE
├─ manage.py
├─ oj
│  ├─ dev_settings.py
│  ├─ production_settings.py
│  ├─ settings.py
│  ├─ urls.py
│  ├─ wsgi.py
│  └─ __init__.py
├─ options
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_auto_20180501_0436.py
│  │  ├─ 0003_migrate_languages_options.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ options.py
│  ├─ tests.py
│  ├─ views.py
│  └─ __init__.py
├─ problem
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_problem__id.py
│  │  ├─ 0003_auto_20170217_0820.py
│  │  ├─ 0004_auto_20170501_0637.py
│  │  ├─ 0005_auto_20170815_1258.py
│  │  ├─ 0006_auto_20170823_0918.py
│  │  ├─ 0008_auto_20170923_1318.py
│  │  ├─ 0009_auto_20171011_1214.py
│  │  ├─ 0010_problem_spj_compile_ok.py
│  │  ├─ 0011_fix_problem_ac_count.py
│  │  ├─ 0012_auto_20180501_0436.py
│  │  ├─ 0013_problem_io_mode.py
│  │  ├─ 0014_problem_share_submission.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ serializers.py
│  ├─ tests.py
│  ├─ urls
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  ├─ utils.py
│  ├─ views
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  └─ __init__.py
├─ README-CN.md
├─ README.md
├─ run_test.py
├─ submission
│  ├─ migrations
│  │  ├─ 0001_initial.py
│  │  ├─ 0002_auto_20170509_1203.py
│  │  ├─ 0005_submission_username.py
│  │  ├─ 0006_auto_20170830_1154.py
│  │  ├─ 0007_auto_20170923_1318.py
│  │  ├─ 0008_submission_ip.py
│  │  ├─ 0009_delete_user_output.py
│  │  ├─ 0011_fix_submission_number.py
│  │  ├─ 0012_auto_20180501_0436.py
│  │  └─ __init__.py
│  ├─ models.py
│  ├─ serializers.py
│  ├─ tests.py
│  ├─ urls
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  ├─ views
│  │  ├─ admin.py
│  │  ├─ oj.py
│  │  └─ __init__.py
│  └─ __init__.py
└─ utils
   ├─ api
   │  ├─ api.py
   │  ├─ tests.py
   │  ├─ _serializers.py
   │  └─ __init__.py
   ├─ cache.py
   ├─ captcha
   │  ├─ Menlo.ttc
   │  ├─ timesbi.ttf
   │  ├─ views.py
   │  └─ __init__.py
   ├─ constants.py
   ├─ management
   │  ├─ commands
   │  │  ├─ inituser.py
   │  │  └─ __init__.py
   │  └─ __init__.py
   ├─ migrate_data.py
   ├─ models.py
   ├─ serializers.py
   ├─ shortcuts.py
   ├─ tasks.py
   ├─ throttling.py
   ├─ urls.py
   ├─ views.py
   ├─ xss_filter.py
   └─ __init__.py

```