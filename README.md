# jenkins-jobs
Base set of Jenkins Jobs for CIRA

Running OSP jobs
================
Please note that the OSP jobs rely on your active RedHat subscription.
In order to authenticate, you need to create a ``/opt/passwords.yml``
file on the slave you want to run your builds. The content of that
file shall be:

rhel_reg_user: <<your_subscription_username>>
rhel_reg_password: <<your_subscription_password>>
rhel_reg_pool_id: <<your_pool_id>>

