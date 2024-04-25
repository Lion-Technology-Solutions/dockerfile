FROM  sonatype/nexus3:latest    

# the nexus volume is used to store nexus content and some config
VOLUME    /nexus-data 


#  the container port
#  what is opened on the aws security group is referred to as [ forwarding port] 
EXPOSE     8081   

USER       nexus    

WORKDIR     /opt/sonatype/nexus   

CMD   ["bin/nexus", "run"]