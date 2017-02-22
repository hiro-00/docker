FROM python:3.5 

RUN  apt-get update \
  && apt-get install -y \
                     wget \
                     unzip \
                     build-essential \
                     xz-utils \
                     python3-pip \
                     libfreetype6-dev \
                     libxft-dev \
                     libblas-dev liblapack-dev libatlas-base-dev gfortran \
  && rm -rf /var/lib/apt/lists/*

#WORKDIR /tmp
#RUN wget https://www.python.org/ftp/python/3.5.0/Python-3.5.0.tar.xz
#RUN tar -xf Python-3.5.0.tar.xz
#WORKDIR /tmp/Python-3.5.0
#RUN ./configure
#RUN make
#RUN make install

#RUN rm -rf /tmp/Python-3.5.0.tar.xz /tmp/Python-3.5.0

RUN pip3 install packaging appdirs ipython numpy scipy matplotlib jupyter pandas sympy scikit-learn tensorflow


RUN cd /home
#RUN wget http://files.grouplens.org/datasets/movielens/ml-20m.zip
#RUN unzip ml-20m.zip -d data



