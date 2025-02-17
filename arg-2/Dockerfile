ARG version
FROM almalinux:${version:-9}
ARG Trainer 
ARG duration 
ARG Course 
RUN echo "Trainer is ${Trainer}, duration is ${duration}, and Course is ${Course}"
ENV DURATION=${duration}
CMD [ "sleep","1000" ]


# docker build -t arg:1.7 --build-arg Trainer=sivakumar --build-arg Coursr=devops --build-arg duration=120hrs .
# env can access both the run time and build but ARG is only at the build time only or image 
