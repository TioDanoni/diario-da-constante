# Diário da Constante · repositório pacman

Este repositório guarda só o pacote `diario-constante` para o pacman (na release `repo`).
O código do projeto fica em outro repositório, privado.

No WolfOS: **WolfOS Hello → Programas → Diário da Constante**.

Em outro Arch, adicione ao `/etc/pacman.conf`:

```ini
[diario-constante]
SigLevel = Optional TrustAll
Server = https://github.com/TioDanoni/diario-da-constante/releases/download/repo
```

```sh
sudo pacman -Syu diario-constante
```

Licença: uso pessoal, todos os direitos reservados.
