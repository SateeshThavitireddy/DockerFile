ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="Docker" \
    AUTHOR="Red Hat Training"
ENV COURSE=${COURSE} \
    AUTHOR=${AUTHOR}
RUN echo "This is a container for the ${COURSE} course by ${AUTHOR}."
CMD ["sleep","1000"]