FROM puterstructions/python3:20161108-2100
MAINTAINER Jason+Flask_Dockerfile@PuterStructions.Com
ENV HW_FLASK_IMAGE_BUILT_AFTER 20161108-2100

RUN pip3 install Flask==0.10.1

ENV file_name=hello_world.py

ADD ${file_name} /${file_name}

CMD /${file_name}
