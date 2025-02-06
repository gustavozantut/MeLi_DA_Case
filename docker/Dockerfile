# base image
FROM jupyter/base-notebook:latest


ARG JUPYTER_TOKEN
ENV JUPYTER_TOKEN $JUPYTER_TOKEN

ARG NB_USER

# Copy requirements.txt file
COPY ./docker/requirements.txt requirements.txt

# Install Python dependencies
RUN pip install -r requirements.txt

# Remove requirements.txt file
RUN rm requirements.txt

# Set the working directory
WORKDIR /home/$NB_USER/work

# Expose necessary ports
EXPOSE 8888