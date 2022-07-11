FROM nginx:1.21.6
LABEL maintainer 'Dustin Leandro <at github.com/DustinCordeiro>'

RUN echo '<h1>Without content</h1>' > /usr/share/nginx/html/content.html
COPY *.html /usr/share/nginx/html/