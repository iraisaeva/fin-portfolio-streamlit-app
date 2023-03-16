FROM python:3.11

WORKDIR /app

COPY requirements.txt ./requirements.txt
COPY front.py ./front.py

RUN pip install -r requirements.txt

EXPOSE 8501

ENTRYPOINT [ "streamlit", "run" ]
CMD [ "Log_in.py" ]

