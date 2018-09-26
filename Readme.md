Hello World!

After 10+ years of being a professional software engineer, I have remarkably little to show for it. No blog posts, no source code on github, no (recorded) talks at conferences. This project will squash the first two, and who knows in the end I will have something interesting to say about it at a conference as well ;).

Aside from building a portfolio, I will use this project to gain experience with some technologies/approaches I have not had a chance to use in my everyday job. The technologies that have my interest are Kotlin, Google App Engine, Sparkjava, undertow, Vaadin 10 and java 9 modules. 

To deploy:
mvn -Dapp.deploy.projectId=joost-baas-blog -Dapp.deploy.version=$(date "+%Y%m%d-%H%M") clean package com.google.cloud.tools:appengine-maven-plugin:deploy
