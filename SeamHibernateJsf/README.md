SeamHibernateJSF
================

In order to start Jetty and deploy demo app execute:

    mvn integration-test

If your DCEVM is installed in different directory than "dcevm" (i.e. in "server") then you may need to execute this:

    mvn -Ddcevm=server integration-test

Now you may go to [http://localhost:8080/SeamHibernateJsf/index.seam](http://localhost:8080/SeamHibernateJsf/index.seam)
