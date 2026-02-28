# Take Pateela

FROM python:3.14

LABEL maintainer = "sarveshgugale09@gmail.com"

# Add ingredients

WORKDIR /app

COPY . .
# mix / process the items

RUN pip install -r requirements.txt

EXPOSE 8000
# Gas on

CMD ["python","main.py"]
