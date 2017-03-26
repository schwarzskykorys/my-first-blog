# my-first-blog / Türkçe

Sanırım bişeyler yanlış yaptım.

###"

###23:34 ~/my-first-blog (master)$ pip install django
###Requirement already satisfied (use --upgrade to upgrade): django in /usr/local/lib/python2.7/dist-packages
###23:35 ~/my-first-blog (master)$ pip install whitenoise
###Collecting whitenoise
###  Using cached whitenoise-3.3.0-py2.py3-none-any.whl
###Installing collected packages: whitenoise
###Exception:
###Traceback (most recent call last):
###  File "/usr/local/lib/python2.7/dist-packages/pip/basecommand.py", line 215, in main
###    status = self.run(options, args)
###  File "/usr/local/lib/python2.7/dist-packages/pip/commands/install.py", line 317, in run
###    prefix=options.prefix_path,
###  File "/usr/local/lib/python2.7/dist-packages/pip/req/req_set.py", line 742, in install
###    **kwargs
###  File "/usr/local/lib/python2.7/dist-packages/pip/req/req_install.py", line 831, in install
###    self.move_wheel_files(self.source_dir, root=root, prefix=prefix)
###  File "/usr/local/lib/python2.7/dist-packages/pip/req/req_install.py", line 1032, in move_wheel_files
###    isolated=self.isolated,
### File "/usr/local/lib/python2.7/dist-packages/pip/wheel.py", line 346, in move_wheel_files
###    clobber(source, lib_dir, True)
###  File "/usr/local/lib/python2.7/dist-packages/pip/wheel.py", line 317, in clobber
###    ensure_dir(destdir)
###  File "/usr/local/lib/python2.7/dist-packages/pip/utils/__init__.py", line 83, in ensure_dir
###    os.makedirs(path)
###  File "/usr/lib/python2.7/os.py", line 157, in makedirs
###    mkdir(name, mode)
### OSError: [Errno 13] Permission denied: '/usr/local/lib/python2.7/dist-packages/whitenoise-3.3.0.dist-info'

### "

### django ve whitenoise kurmaya çalıştığımda python anywhere'ye, bu sorunu veriyor.

## bilen birisi bana bkorayaltan@gmail.com adresinden ulaşabilirmi rica etsem?
