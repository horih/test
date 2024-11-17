FROM horih/satysfi:latest 

RUN eval $(opam env) && opam pin add "git+https://github.com/puripuri2100/satysfi-class-template.git" -y && opam update && opam install -y\
    satysfi-class-stjarticle \
    satysfi-class-template \
    satysfi-latexcmds \
    satysfi-easytable \
    satysfi-figbox \
    satysfi-code-printer \
    satysfi-image \
    satysfi-json \
    satysfi-num-conversion \
    && satyrographos install

