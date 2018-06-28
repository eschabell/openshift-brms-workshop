Update: June 2018 moved to [Gitlab](https://gitlab.com/eschabell/openshift-brms-workshop).

# Deprecated: 

-----

This project was based on OpenShift v2, a new version is available 
for [OpenShift Container Platform](https://github.com/redhatdemocentral/rhcs-coolstore-demo).

-----

Red Hat JBoss BRMS Workshop
===========================
This git repository helps you get up and running quickly with a 
Cloud hosted workshop on JBoss BRMS that gets you
started building your very own Cool Store retail webshop.

The web shop project will have you designing guided rules, technical rules, 
a decision table, a ruleflow, and deploying a Java WAR of the web shop.


Install with one click
----------------------
[![Click to  install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to  install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=ruby-2.0&initial_git_url=https://github.com/eschabell/openshift-brms-workshop.git&name=brmsworkshop)


Manual setup on OpenShift
-------------------------
Create an account at http://openshift.redhat.com/

Create a ruby application

    rhc app create brmsworkshop -t ruby-2.0 --from-code git://github.com/eschabell/openshift-brms-workshop.git

That's it, you can now start your workshop at:

    http://brmsworkshop-$your_domain.rhcloud.com

![Cool Store Workshop](https://raw.githubusercontent.com/eschabell/openshift-brms-workshop/master/lib/images/brms_bpms_workshop/header.png)

![Cool Store App](https://raw.githubusercontent.com/eschabell/openshift-brms-workshop/master/lib/images/brms_bpms_workshop/image125.png)
