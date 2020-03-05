# supersonic-subatomic-java

## Contents at a Glance.
* [AOT Compilation](#aot-compilation)
* [GraalVM](#graalvm)
* [Quarkus](#quarkus)
* [Micronaut](#micronaut)
* [Kubernetes](#kubernetes)
* [Cloud](#cloud)
* [Serverless Application](#serverless-application)
* [Articles](#articles)
* [About](#about)
* [Help](#help)






> ## AOT Compilation.
> * [Ahead-of-time compilation (AOT).](https://www.google.com/search?q=aot+compiler&oq=AOT+compiler&aqs=chrome.0.0l8.11638j0j7&sourceid=chrome&ie=UTF-8)
> * []()
> * []()
> * []()






> ## JIT Compilation.
> * [Just-in-time compilation (JIT).](https://www.google.com/search?q=jit+compiler&oq=jit+&aqs=chrome.2.69i57j0l5j69i65l2.7170j0j7&sourceid=chrome&ie=UTF-8)
> * []()
> * []()
> * []()






> ## GraalVM.
> * [GraalVM.](https://www.graalvm.org/)
> * [Generation platform dependent code.]()
> * [Closed World Assumption.](https://www.google.com/search?q=Closed+World+Assumption+graalvm&oq=Closed+World+Assumption+graalvm&aqs=chrome..69i57.10634j0j7&sourceid=chrome&ie=UTF-8)
> * []()
> * []()
>> ### Conferences and Seminars
>>> * [Ten Things You Can Do With GraalVM - Oleg Šelajev](https://www.youtube.com/watch?v=tEaEAq0L9Pk)
>>> 1. High-Performance modern Java.
>>> 2. Low-footprint, fast-startupJava.
>>> 3. Combine Java, R, JavaScript, Ruby.
>>> 4. Run native languages on the JVM.
>>> 5. Tools that work across all languages.
>>> 6. Extend a JVM-based application.
>>> 7. Extend a native application.
>>> 8. Java code as a native library.
>>> 9. Polyglot in the database.
>>> 10. Create you own language.






> ## Quarkus.
> * [Quarkus.](https://quarkus.io/)
> * [QUTE REFERENCE GUIDE](https://quarkus.io/guides/qute-reference)
> * [Hot Reload.]()
> * [Reactive Programming Style.]()
> * [DEPLOYING ON KUBERNETES AND OPENSHIFT](https://quarkus.io/guides/deploying-to-kubernetes)
> * [EXTENSIONS.](https://quarkus.io/extensions/)
> * [Platform Dependent Application.]()
> 
> * []()
> * []()
>
>> ### Maven Commands.
>> * `mvn quarkus:dev` Running the application in dev mode.
>> * `mvn compile quarkus:dev` Compile the application in dev mode.
>> * `mvn quarkus:list-extensions` Show list of extensions.
>> * `mvn quarkus:add-extension -Dextensions="groupId:artifactId"` Adding extension.
>> * `mvn package` For packaging application. Be aware that it’s not an _über-jar_ as the dependencies are copied into the `target/lib` directory.
>> * `mvn package -Pnative -Dquarkus.native.container-build=true` You can use Docker to build the native executable.
>
>> ### Building a native executable.
>> * [Building a native executable.](https://quarkus.io/guides/building-native-image)
>>
>>> #### Commands. 
>>> `mvn package -Pnative` Compilation into native code.
>>>> ##### Preparation environment to build native executable.
>>>> * `sudo update-alternatives --install /usr/bin/java java /path/.../bin/java 13`
>>>> * `sudo update-alternatives --install /usr/bin/javac javac /path/.../bin/javac 13`
>>>> * `sudo update-alternatives --install /usr/bin/javadoc javadoc /path/.../bin/javadoc 13`.<br/><br/>
>>>> * `sudo update-alternatives --config java`
>>>> * `sudo update-alternatives --config javac`
>>>> * `java -version`
>>>> * `javac -version`.<br/><br/>
>>>> * `export JAVA_HOME=/pathToMainFolder`
>>>> * `echo $JAVA_HOME`
>>>> * `export PATH=$JAVA_HOME/bin:$PATH`.<br/><br/>
>>>> * `export GRAALVM_HOME=/pathToMainFolder`
>>>> * `echo $GRAALVM_HOME`
>>>> * `export PATH=$GRAALVM_HOME/bin:$PATH`.<br/><br/>
>>>> * `source /home/trl/.profile`.<br/><br/>
>>>> * `$GRAALVM_HOME/bin/gu install --file native-image-installable-svm-svmee-java11-linux-amd64-20.0.0.jar`
>
>> ### Courses.
>> * []()
>
>> ### Conferences.
>> * []()
>
>> ### Articles.
>> * [Quarkus — сверхзвуковая субатомная Java. Краткий обзор фреймворка.](https://habr.com/ru/company/haulmont/blog/443242/)
>> * [Quarkus: Сверхзвуковая субатомная ветклиника.   ](https://habr.com/ru/company/haulmont/blog/487588/)
>> * []()






> ## Micronaut.
> * [Micronaut.](https://micronaut.io/)
> * []()
> * []()
> * []()





> ## Docker.
> * []()
> * []()
> * []()





> ## Kubernetes.
> * [Kubernetes.](https://kubernetes.io/)
> * [Local Caching. Caches of different nodes are not synchronized with each other.]()
> * []()
> * []()





> ## Cloud.
> * [What are clouds?](https://www.redhat.com/en/topics/cloud)
> * [What are cloud-native applications?](https://www.redhat.com/en/topics/cloud-native-apps)
> * [Hybrid Cloud.](https://www.google.com/search?q=hybrid+cloud&oq=hybrid&aqs=chrome.1.69i57j0l7.5308j0j7&sourceid=chrome&ie=UTF-8)
> * []()





> ## Serverless Architecture.
> * [Backend as a Service (BaaS)](https://www.google.com/search?q=backend+as+a+service&oq=Backend+as+a+Service&aqs=chrome.0.0l8.829j0j7&sourceid=chrome&ie=UTF-8).
>> ### Function as a Service (FaaS).
>> * [Function as a Service (FaaS)](https://www.google.com/search?newwindow=1&safe=active&sxsrf=ALeKk03suemQ01Rcvkby-NMGUxC9iQ6ynw%3A1583426379916&ei=SythXpzPN4u9lwTGkaHACg&q=function+as+a+service&oq=function+as+a+service&gs_l=psy-ab.3..0i7i30l5j0l5.57855.62829..63847...0.2..0.122.1377.9j5......0....1..gws-wiz.......0i71j35i304i39j0i273j0i8i7i30.lE---hpjwmM&ved=0ahUKEwjcoJz34oPoAhWL3oUKHcZICKgQ4dUDCAs&uact=5).
>>> #### Peculiar properties.
>>> * Independent functions.
>>> * Ephemeral.
>>> * Stateless.
>>> * Event-triggered.
>>> * Scalable by default.
>>> * Fully managed by cloud vendor.
>
>> ### Pros and Cons.
>> #### Pros.
>> * Focus on your code, not the infrastructure.
>> * Fast delivery of feature.
>> * Lower operational and development cost.
>> * No software or runtime to install or maintenance.
>> * Experiment and innovate quickly.
>> * Zero system administration.<br/><br/>
>> * Scalability out of the box.
>> * Scale up and down with demand.<br/><br/>
>> * Monitoring out of the box.<br/><br/>
>> * Never pay for idle resources.
>> * Pay for consistent throughput or execution duration rather that by server unit.
>>
>> #### Cons.
>> * Vendor lock-in.  
>> * Function could start.
>> * Hard to test and debug.
>> * Unsuitable for long-running tasks.
>> * Architectural complexity. 
>> * Cloud vendor limits.
>
>> ### Courses.
>> * [Serverless Architecture.](https://www.youtube.com/playlist?list=PLvTBThJr861xrJAVklH2E8JYR5FqPxTY8)
>
>> ### Conferences.
>> * [Введение в Serverless архитектуру.](https://www.youtube.com/watch?v=ZRg1jMaMP7U&feature=youtu.be)
>
>> ### Articles.
>> * [Serverless Application.](https://www.google.com/search?q=serverless+application&oq=serverless+ap&aqs=chrome.3.69i57j0l7.13472j0j7&sourceid=chrome&ie=UTF-8)





> ## Amazon Web Services (AWS).
>
>> ### AWS Lambda.
>
>> ### Amazon API Gateway.
>
>> ### Amazon S3.
>
>> ### Identity and Access Management (IAM).





> ## Microsoft Azure.





> ## Google Cloud Platform.





> ## Alibaba Cloud.





> ## Oracle Cloud.





> ## IBM Cloud.




> ## Yandex Cloud





> ## Others Courses.





> ## Others Conferences.






> ## Others Articles.
> * [Classification of Development Frameworks for Enterprise Apps.](https://dzone.com/articles/classification-of-development-frameworks-for-enter)
