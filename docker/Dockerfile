# python3.8 lambda base image
#FROM public.ecr.aws/lambda/python:3.8
FROM public.ecr.aws/lambda/python:3.8-x86_64

COPY . ./
#COPY ./scripts /

# installing dependencies
RUN pip3 install -r ./docker/requirements.txt
