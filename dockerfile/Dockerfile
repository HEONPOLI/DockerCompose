FROM python
RUN git clone https://github.com/HEONPOLI/Django-Mysql.git 
RUN pip3 install -r /Django-Mysql/requirements.txt
RUN pip3 install pymysql
RUN mkdir /templates && cp /Django-Mysql/templates/* /templates
RUN mkdir /static && cp -r /Django-Mysql/static/* /static
CMD python3 /Django-Mysql/manage.py runserver 0.0.0.0:8000

