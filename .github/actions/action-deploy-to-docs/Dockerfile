FROM debian:9.5-slim

LABEL "com.github.actions.name"="Deploy to Docs"
LABEL "com.github.actions.description"="Deploy to to github pages (/docs)"
LABEL "com.github.actions.icon"="book-open"
LABEL "com.github.actions.color"="orange"

LABEL "repository"="https://github.com/chanan/BlazorActions"
LABEL "homepage"="https://github.com/chanan/BlazorActions"
LABEL "maintainer"="Chanan Braunstein <chanan@bkbunch.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]