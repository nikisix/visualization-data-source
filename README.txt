To compile everything and install all jars in the maven repository on your local machine do this
at the top level directory

   mvn install

Then in the examples directory, you can do this to run a stand-alone Jetty web server:

   mvn jetty:run

Go to http://localhost:8080/all_examples.html to see the examples in action.

For instructions on how to run the examples refer to: http://code.google.com/apis/visualization/documentation/dev/dsl_get_started.html
