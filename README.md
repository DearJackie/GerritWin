Package with scripts to configure gerrit on windows

NOTE:
a) Make sure to rename the .war package to "gerrit.war" before running the scripts.
b) current package is gerrit-3.0.0.war.
c) JRE 1.8 shall be ready.
d) "ssh-keygen.exe" commands in "bin" copied from "git for windows", as the initialization phase needs this command.

HOW:
1. to configure and set up gerrit site, run "init.bat", this will also automatically start the daemon
2. to run daemon, run "daemon_run.bat" 

3. to open gerrit web interface, goto ".\gerrit_review_site\etc\gerrit.config",
   copy the URL from "canonicalWebUrl" to web browser
