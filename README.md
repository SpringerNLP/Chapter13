# Chapter 13 - Deep Reinforcement Learning for Text and Speech

## Requirements
* [Docker](https://docs.docker.com/install/) 
* [Nvidia docker2](https://github.com/nvidia/nvidia-docker/wiki/Installation-(version-2.0)#installing-version-20)


## Data
data/processed_train.bin
data/vocab-50k
data/processed_test.bin

## Running the Docker Image
The docker images for this case study are located on dockerhub. Running the commands below will automatically download and start a jupyter notebook.

Run the Docker image:
```
docker run --runtime=nvidia -p 8888:8888 -p 6006:6006 springernlp/chapter_13:latest
```

## Book Reference
More information can be found at: [Deep Learning for NLP and Speech Recognition](https://www.amazon.com/Deep-Learning-NLP-Speech-Recognition/dp/3030145956) by [Springer](https://www.springer.com/us/book/9783030145958) 
