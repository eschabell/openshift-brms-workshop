Awestruct JBoss BMRS 6 Workshop on OpenShift 
============================================
This git repository helps you get up and running quickly with a ruby based
Awestruct generated site to host the workshop on JBoss BRMS that gets you
started building your very own Cool Store retail webshop.

The web shop project will have you designing guided rules, technical rules, 
a decision table, a ruleflow, and deploying a Java WAR of the web shop.

Enjoy!

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a ruby application

    rhc app create brmsworkshop -t ruby-1.9 --from-code git://github.com/eschabell/openshift-brms-workshop.git

That's it, you can now start your workshop at:

    http://brmsworkshop-$your_domain.rhcloud.com

