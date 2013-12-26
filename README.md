Play framework 2 application on OpenShift Express
============================

This is a fork of https://github.com/opensas/play2-openshift-quickstart

The approach is a bit different here :

You install Play2 on OpenShift with ssh, such as : 

    cd app-root/data
    curl http://downloads.typesafe.com/play/2.2.1/play-2.2.1.zip > play.zip
    unzip play.zip
    rm play.zip

Then you only push the source changes via git.

TODO : point to the config files you need to change.
