#ARG version
FROM almalinux:8 
# ${version:-8}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Course: ${COURSE}, Trainer: ${TRAINER}, Version: ${version}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]