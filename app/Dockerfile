FROM python:3.6-alpine
LABEL maintainer="sop.damienleroy@gmail.com"
WORKDIR /opt
COPY . .
RUN pip install flask==1.1.2
EXPOSE 8080
ENV ODOO_URL='odoo-web-svc:30008' \
    PGADMIN_URL='pgadmin-web-svc:30009'
CMD ["python", "./app.py"]
