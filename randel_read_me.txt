# https://github.com/uoip/pangolin/issues/33

cmake -DBUILD_PANGOLIN_FFMPEG=OFF -DPYBIND11_PYTHON_VERSION=3.8 ..
make -j17