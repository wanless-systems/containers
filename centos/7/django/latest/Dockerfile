FROM centos:centos7

RUN yum -y update
RUN yum -y install install python3 python3-pip python3-devel openssl-devel libffi-devel gcc gcc-c++ make openldap-devel
RUN yum clean all
RUN pip3 install --upgrade pip
RUN pip3 install --upgrade \
        channels \
        channels_redis \
        coreapi \
        django \
        django-auth-ldap \
        django-bootstrap4 \
        django-fa \
        django-filter \
        djangorestframework \
        drf-yasg[validation] \
        gunicorn \
        markdown \
        psycopg2-binary \
        pygments

CMD ["/bin/bash"]
