FROM bash

COPY app app
COPY . .

LABEL com.ngageoint.seed.manifest=""

RUN chmod -R 777 app

ENTRYPOINT ["/app/job.sh"]
