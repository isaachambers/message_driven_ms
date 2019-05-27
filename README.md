# Generate Command for Demo Service /n mvn io.fabric8:vertx-maven-plugin:1.0.5:setup -DprojectGroupId=io.vertx.microservice -DprojectArtifactId=message_driven_ms -Dverticle=io.vertx.isaachambers.message.HelloMicroservice -Ddependencies=infinispan


TO run this project, Run with command.


mvn compile vertx:run -Dvertx.runArgs="-cluster -Djava.net.preferIPv4Stack=true"
The -cluster tells Vert.x to start in cluster mode.