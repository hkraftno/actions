FROM node:10-alpine

LABEL "com.github.actions.name"="Deploy to hkraft.no"
LABEL "com.github.actions.description"="Deploys the hkraft.no site"
LABEL "com.github.actions.icon"="terminal"
LABEL "com.github.actions.color"="blue"

LABEL "repository"="http://github.com/hkraftno/actions"
LABEL "homepage"="https://hkraft.dev"
LABEL "maintainer"="Petter Hareim <petter.hareim@hkraft.no>"

ADD entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]