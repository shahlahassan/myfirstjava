FROM java:7
COPY HelloWorld.java /
RUN javac HelloWorld.java
ENTRYPOINT ["java","HelloWorld"]
RUN mkdir /data/myvolume -p
RUN echo "Testing">> /data/myvolume/text
VOLUME data/myvolume



