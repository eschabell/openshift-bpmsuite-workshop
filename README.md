Reveal.js JBoss BPM Suite Workshop on OpenShift 
===============================================
This git repository helps you get up and running quickly with a PHP based
reveal.js site to host the workshop on JBoss BPM Suite that gets you
started building your very own employee rewards process.

Enjoy!

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create bpmworkshop -t php-5.4 --from-code git://github.com/eschabell/openshift-bpmsuite-workshop.git

That's it, you can now start your workshop at:

    http://bpmworkshop-$your_domain.rhcloud.com

![Rewards Workshop](https://raw.githubusercontent.com/eschabell/openshift-bpmsuite-workshop/master/php/cover.png)

