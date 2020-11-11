FROM ubuntu

RUN apt update && DEBIAN_FRONTEND=noninteractive apt install --no-install-recommends -y \
        python3 python3-pip texlive texlive-extra-utils texlive-base git \
        latexmk texlive-xetex texlive-pstricks texlive-science texlive-publishers \
    && pip3 install pygments \
    && rm -rf /var/cache/apt/*