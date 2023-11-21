FROM nginx
LABEL "Project"="hrms-django-application"
LABEL "Author"="Nithya"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY hrms.conf /etc/nginx/conf.d/hrms.conf
