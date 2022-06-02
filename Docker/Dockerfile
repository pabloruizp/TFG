FROM pytorch/manylinux-cuda111
RUN yum install python3-devel -y
RUN yum install ffmpeg libsm6 libxext6  -y
RUN python3 -m pip install -U pip
WORKDIR "/root"
RUN git clone https://github.com/pabloruizp/YOLOX.git
WORKDIR "/root/YOLOX"
RUN pip3 install torch
RUN pip3 install -r requirements.txt
RUN python3 setup.py develop
