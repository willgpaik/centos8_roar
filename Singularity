BootStrap: docker
From: centos:8

%setup

%files

%environment
    
%runscript

%post
    dnf install -y epel-release centos-release-scl
    dnf group install -y "Development Tools"
    dnf group install -y "Base"
    dnf install -y vim \
            git \
            cmake \
            gcc \
            gcc-c++ \
            gcc-gfortran \
            python2-devel \
            python2-pip \
            python38-devel \
            python38-pip \
            patch \
            openss-devel \
            pcre-devel \
            mesa-libGL-devel \
            mesa-libGLU-devel \
            glibc-devel \
            Lmod \
            qt5-qtbase-devel \
            qt5-qtcharts-devel \
            qt5-qtsvg-devel \
            qt5-qtx11extras-devel \
            libX11-devel \
            libXpm-devel \
            libXft-devel \
            libXext-devel \
            gsl-devel \
            hdf5-devel \
            bzip2-devel \
            zlib-devel \
            libcurl-devel \
            ca-certificates \
            autoconf \
            tix \
            tk-devel \
            python2-tkinter \
            python38-tkinter \
            libxkbcommon-devel \
            libxkbcommon-x11 \
            readline-devel
    dnf -y update
    
