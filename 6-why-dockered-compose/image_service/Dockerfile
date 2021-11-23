# 1. image python
FROM python:3

WORKDIR /src

# 2. nakopírovat zdrojáky
COPY compute_engine.py /src
COPY requirements.txt /src

# 3. nainstalovat python3-opencv (apt-get)
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "-y", "python3-opencv"]

# 4. nainstalovat pip requirements.txt
RUN ["python", "-m", "pip", "install", "-r", "requirements.txt"]

# 5. definovat entrypointy/cmd
CMD ["python", "compute_engine.py"]
