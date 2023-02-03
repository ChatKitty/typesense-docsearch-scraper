FROM typesense/docsearch-scraper-base
LABEL maintainer="development@chatkitty.com"

WORKDIR /root
COPY scraper/src ./src

ENTRYPOINT ["pipenv", "run", "python", "-m", "src.index"]
