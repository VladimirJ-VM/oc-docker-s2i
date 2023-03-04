# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# CMD ["/bin/bash", "-c", "sleep infinity"]
# Remove the # from the start of the following line (originally line 6 in Dockerfile) to make the instruction executable
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
