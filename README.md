Red Hat JBoss BPM Suite Workshop
================================
This git repository helps you get up and running quickly with a 
cloud hosted workshop on JBoss BPM Suite that gets you
started building your very own employee rewards process.

Install with one click
----------------------
[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to
install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.4&initial_git_url=https://github.com/eschabell/openshift-bpmsuite-workshop.git&name=bpmworkshop)

Manual setup on OpenShift
-------------------------

Create a PHP application

    rhc app create bpmworkshop -t php-5.4 --from-code git://github.com/eschabell/openshift-bpmsuite-workshop.git

That's it, you can now start your workshop at:

    http://bpmworkshop-$your_domain.rhcloud.com

![Rewards Workshop](https://raw.githubusercontent.com/eschabell/openshift-bpmsuite-workshop/master/php/cover.png)

