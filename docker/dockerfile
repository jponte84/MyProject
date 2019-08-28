FROM busybox

ADD hello-world /bin/hello-world
COPY target/java-archive-1.0-SNAPSHOT.jar /

ENV NAME=world
ENTRYPOINT ["/bin/hello-world"]
