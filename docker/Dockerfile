# The Queen's University of Belfast ECIT 2018
# This file is subject to the terms and conditions defined in
# file 'LICENSE.md', which is part of this source code package.
#
# User ID mapping reference from:
#   https://gist.github.com/renzok/29c9e5744f1dffa392cf

FROM ubuntu:24.04

# initial setup and package install
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
  apt-get install -y \
  build-essential \
  pkg-config \
  autoconf \
  automake \
  libtool \
  autotools-dev \
  autoconf-archive \
  subunit \
  gmpc \
  check \
  graphviz \
  zip
