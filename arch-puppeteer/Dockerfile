FROM archlinux:latest
RUN pacman --noconfirm -Sy nodejs npm xorg-server-xvfb chromium
RUN pacman --noconfirm -Syuu
RUN useradd -ms /bin/bash runner
USER runner
