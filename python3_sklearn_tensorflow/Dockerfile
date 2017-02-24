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


RUN pip3 install packaging appdirs ipython numpy scipy matplotlib jupyter pandas sympy scikit-learn tensorflow


#RUN cd /home
#RUN wget http://files.grouplens.org/datasets/movielens/ml-20m.zip
#RUN unzip ml-20m.zip -d data



