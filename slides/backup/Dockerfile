FROM debian:11-slim
WORKDIR /root

RUN apt update && \
    apt install -y toilet cmake build-essential python3 pip git zip file ghostscript pdftk paps&& \
    echo "alias ll='ls -la --color'" >> .bashrc && \
    echo "echo 'Welcome to ' | toilet -t --gay" >> .bashrc && \
    echo "echo 'Password Security' | toilet -t --gay" >> .bashrc && \
    echo "echo $'\n'" >> .bashrc && \
    echo 'echo -e "\e[1;5;32mDocker Image da utilizzare solo per l'"'"'esercitazione del prof Mancuso\e[0m"' >> .bashrc 
&& \
    echo "echo $'\n'" >> .bashrc && \
    git clone https://github.com/openwall/john && \
    cd john/src && \
    ./configure --without-openssl && \
    make -j2 && \
    cd ../run && \
    cp -Rv * /usr/sbin && \
    cd /root && \
    rm -rf hashcat john && \
    pip install --user pyhanko==0.20.1 && \
    echo "Se leggi se un hacker!!!" > secret.txt && \
    zip -e -P pinky009 secret secret.txt && \
    paps secret.txt | ps2pdf - _secret.pdf && \
    pdftk _secret.pdf output secret.pdf user_pw 513513513 && \
    rm -f _secret.pdf && \
    rm -f secret.txt && \
    apt purge -y cmake build-essential git ghostscript pdftk paps && \
    apt autoremove -y && \
    apt install -y libgomp1



CMD ["/bin/bash"]

