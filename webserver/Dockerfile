FROM tiangolo/uvicorn-gunicorn-fastapi:python3.7

COPY requirements.txt /app/

RUN pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple && \
  pip install --no-cache-dir -r /app/requirements.txt

COPY . /app
