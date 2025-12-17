FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
LABEL course="devops" \
      trainer="siva anna" \
      learner="chandu"
CMD [ "nginx","-g","daemon off;" ]
COPY index.html /usr/share/nginx/html/index.html