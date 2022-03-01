**refer to github{@theniceboy, @WindyVally}**

---

已安装补丁列表：

+ alpha-0.8.2
+ anysize-0.8.1
+ clipboard-0.8.2
+ dracula-0.8.2
+ font2-20190416-ba72400
+ scrollback-20190331-21367a0

官方原文件如下：

st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

