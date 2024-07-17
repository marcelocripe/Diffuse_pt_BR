Comparador de Arquivos Diffuse

Repositório oficial do programa "Diffuse"

https://github.com/MightyCreak/diffuse/ e https://github.com/lxde/lxappearance/blob/master/po/pt_BR.po

Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/Diffuse_pt_BR/blob/main/diffuse_pt_BR.po
https://github.com/marcelocripe/Diffuse_pt_BR/blob/main/io.github.mightycreak.Diffuse.desktop


Para utilizar o arquivo "diffuse_pt_BR.po" e o "io.github.mightycreak.Diffuse.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"diffuse_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt diffuse_pt_BR.po -o diffuse.mo


Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp diffuse.mo /usr/share/locale/pt_BR/LC_MESSAGES


"io.github.mightycreak.Diffuse.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp io.github.mightycreak.Diffuse.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
