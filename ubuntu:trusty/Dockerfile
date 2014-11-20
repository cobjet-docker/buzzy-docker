FROM buzzy/build-ubuntu:trusty

RUN sudo apt-get install -y curl \
 && curl -O http://public.redjack.com/ubuntu:trusty/buzzy_0.5.0_amd64.deb \
 && sudo dpkg -i buzzy_*.deb \
 && sudo apt-get install -y -f \
 && sudo apt-get clean \
 && rm buzzy_*.deb
