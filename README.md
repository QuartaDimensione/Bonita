Tomcat 7.0.67 & Bonitasoft & Postgres  on OpenShift
===================



How to use
----------

Create a DIY application

    rhc app create -a tomcat -t diy-0.1

Get Bonita  running

    cd tomcat
    git remote add upstream -m master git://github.com/QuartaDimensione/Bonita.git
    git pull -s recursive -X theirs upstream master
    git push
