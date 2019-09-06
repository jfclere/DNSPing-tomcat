# DNSPing-tomcat
DNS ping demo with war

It uses an image based on https://github.com/jfclere/DNSPing-tomcat.git

What is important to remember:

ARG namespace=tomcat

ENV KUBERNETES_NAMESPACE=$namespace

So the name should be give or tomcat must be used.

Use https://github.com/jfclere/tomcat-openshift to build docker image.
