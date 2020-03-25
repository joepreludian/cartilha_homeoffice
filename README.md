# Plataforma de apoio ao Homeoffice

@todo insira um Sobre bacana

## Trabalhando no projeto - Usando Docker

O método mais rápido para trabalhar na ferramenta é utilizar a ferramenta Docker;
Como estou utilizando Fedora 31, utilizo o Podman. Para usar o docker, basta trocar o nome de `podman` para `docker`.

    $ sudo podman run --rm -v $(pwd):/srv/jekyll -p 4000:4000 -it jekyll/jekyll:3.8 jekyll serve
