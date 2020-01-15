FROM gcr.io/google.com/cloudsdktool/cloud-sdk:alpine

LABEL "com.github.actions.name"="Build hkraft.no"
LABEL "com.github.actions.description"="Builds the hkraft.no site"
LABEL "com.github.actions.icon"="terminal"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="http://github.com/hkraftno/actions"
LABEL "homepage"="https://hkraft.dev"
LABEL "maintainer"="Hkraft.no <utvikling@hkraft.no>"

RUN gcloud components install gsutil cloud-build-local docker-credential-gcr

RUN apk --update add git less openssh && \
    rm -rf /var/lib/apt/lists/* && \
    rm /var/cache/apk/*