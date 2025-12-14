]# Kernel custom (Bluetooth desativado)

Este repositório não contém o código inteiro do kernel.
Ele guarda a configuração e instruções para reproduzir a build.

## Como compilar
1) Baixe o kernel (ex: 6.6.67) do kernel.org
2) Copie `config-bt-off` para `.config`
3) Rode: `make olddefconfig`
4) Compile: `make -j$(nproc)`

## Garantia do Bluetooth OFF
No .config:
- CONFIG_BT=n

## Alunos
Riquelmi Neves
Grazielle Cristina
Luiza Oliveira
Sofia Fernandes
Wata Monteiro
