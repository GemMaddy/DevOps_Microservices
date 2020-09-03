FROM python:3.7.3-stretch
# Comments
WORKDIR /app
# Comments
COPY . flask_app/web.py /app/
# Comments
RUN pip install --upgrade pip && pip install --trusted-host pypi.python.org -r requirements.txt
# Comments
EXPOSE 80
# Comments
CMD ["python", "web.py"]