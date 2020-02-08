FROM registry.access.redhat.com/ubi8/ubi:8.0
USER 1001
RUN mkdir logs
CMD bash -c "while true; do echo test >> logs/app.log ; sleep 10; done"
