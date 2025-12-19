ARG VERSION
FROM almalinux:${VERSION:-8}
ARG course="DEVOPS" \ 
    trainer="SivaAnna" \
    duration="10hrs"
RUN course=${course}
RUN echo "COURSE: ${course},TRAINER: ${trainer},DURATION: ${duration},VERSION: ${VERSION}"
CMD ["sleep","1000"]