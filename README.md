# train-schedule-kube-jimmys

This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.
Original title: "cicd-pipelines-train-schedule-kubernetes.
I have made changes to the original project, but only in terms of which gradle wrapper to use to make it work with Java version 11.
In addition to that I made some configuration changes as well.
Had to change which node version was used and change plugin for it to work with gradle version 6.


## Running the app

You need a Java JDK 11 or later to run the build. 
In addition, you need gradle version 6 or later.

You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at http://localhost:8080
