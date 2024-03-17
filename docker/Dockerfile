FROM odoo:17.0

USER root


COPY ./requirements.txt /requirements.txt

RUN python3 -m pip install pip --upgrade
RUN pip3 install -r /requirements.txt
RUN rm /requirements.txt
