#Quick Hello World

Run this by running `mvn exec:java`.  This will download all dependencies, build the project, and run it. You can also
use the included Dockerfile to build a container.

By default, the service runs on port 4567 and responds to requests at /

Query Params: 

* lang (2-char code), defaults to 'en'
* name - name to use, defaults to 'World!'

Running in Docker:

docker build -t cf-hello-world .

docker run -d --name cf-hello-world -p 4567:4567 cf-hello-world

To make the automated unit test fail, go to src/test/java/BasicUnitTest.java and uncomment the second line in the 'runTest' method.

