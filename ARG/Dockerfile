ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    TRAINER="SIVA" 
ENV COURSE=${COURSE}
RUN echo "Trainer: ${TRAINER}, Course: ${COURSE}"
CMD [ "sleep" , "1000" ]