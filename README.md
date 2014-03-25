Ruby Awestruct Workshop on OpenShift 
====================================
This git repository helps you get up and running quickly with a ruby based
Awestruct generated site, using real.js for slides to host a workshop.

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a ruby application

    rhc app create brmsworkshop -t ruby-1.9 --from-code git://github.com/eschabell/openshift-brms-workshop.git

That's it, you can now checkout your application at:

    http://brmsworkshop-$your_domain.rhcloud.com

