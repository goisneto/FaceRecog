web: ((git clone https://github.com/opencv/opencv.git && cd opencv && CFLAGS="-fPIC" && export CFLAGS && export C_INCLUDE_PATH=/include:/usr/include:/usr/local/include:$(pwd)/include && export CPLUS_INCLUDE_PATH=/include:/usr/include:/usr/local/include:$(pwd)/include && mkdir release && cd release && cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local .. && make && export PATH=$PATH:$(pwd)/bin && export LD_LIBRARY_PATH=/lib:/usr/lib:/usr/local/lib:$(pwd)/lib && export C_INCLUDE_PATH=/include:/usr/include:/usr/local/include:$(pwd)/include && export CPLUS_INCLUDE_PATH=/include:/usr/include:/usr/local/include:$(pwd)/include && cd .. && cd .. && cd opencv-facerecog && ./run.sh && export PATH=$PATH:$(pwd) && cd ..)&) && node proc.js
