FROM python:3.9-slim
WORKDIR /opt/app
COPY . /opt/app
# RUN 실행해라는 명령어
RUN pip install -r requirements.txt
# 컨테이너 실행됐을때 실행할 명령어
CMD ["python3", "app.py"]