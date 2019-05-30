FROM python:latest

RUN apt-get update

# Install requirements
# RUN pip install -U -r requirements.txt

ENV APP_ROOT /src

WORKDIR $APP_ROOT

RUN chmod +x $APP_ROOT \
	&& pip install --upgrade pip

# Define default command.
CMD ["/bin/sleep", "100000000"]