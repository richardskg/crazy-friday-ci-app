#Quick Hello World

Run this by running `mvn exec:java`.  This will download all dependencies, build the project, and run it. You can also
use the included Dockerfile to build a container.

By default, the service runs on port 4567.

Query Params: 
* lang (2-char code), defaults to 'en'
* name - name to use, defaults to 'World!'
