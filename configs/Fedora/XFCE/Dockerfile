FROM lscr.io/linuxserver/webtop:fedora-xfce
LABEL org.opencontainers.image.authors="K.B.Dharun Krishna mail@kbdharun.dev"
LABEL description="This image is based on \
the Linuxserver.io Fedora image using XFCE as the desktop environment \
along with additional packages of programming languages for development."

# Preinstall popular programming languages and package managers
RUN dnf install -y @development-tools \
    curl wget git \
    python3 python3-pip jupyter-notebook tldr \
    gcc golang gcc-c++ make clang gcc-gfortran \
    gjs gjs-devel \
    java-devel java-openjdk \
    rust cargo nodejs \
    meson ninja-build \
    podman distrobox \
    elixir lua julia haskell-platform \
    perl-core php-cli R ruby swiftlang \
    mariadb postgresql postgresql-server \
    sqlite sqlite-devel sqlite-tcl sqlitebrowser redis