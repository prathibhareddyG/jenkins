# jenkins
jenkins with parameterised build
java -jar jenkins.war --httpPort=8090  (these command for to run another port) 
create a new job in freestyle job
general==>parameterised job==>select parameter==>execute shell(in build)
SYNTAX
windows = %parametername@
linuc/mac = $parametername  ${parametername}  "${parametername}
