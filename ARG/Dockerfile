ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="nagendra" \
    duration="120HRS"
ARG USERNAME=Nagendra
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]
