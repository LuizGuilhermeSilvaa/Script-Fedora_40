# ScriptsLinux-Fedora 40 Workstation

## Script Plymouth

- Adicionar tema no caminho -> /usr/share/plymouth/themes
- sudo dnf install plymouth-plugin-script (Caso não tenha plymouth-plugin)
- sudo plymouth-set-default-theme -R {NOME DO TEMA}

- Obs: Comando para saber tema atual: cat /etc/plymouth/plymouthd.conf

## Atualizar GRUB 

- sudo grub2-mkconfig -o /boot/grub2/grub.cfg

## Colocar GRUB em 1920x1080

- sudo nano /etc/default/grub
- Adicionar linha: GRUB_GFXPAYLOAD_LINUX=1920x1080
- Salvar alterações
- Atualizar GRUB: sudo grub2-mkconfig -o /boot/grub2/grub.cfg


# Fontes

- [https://diolinux.com.br/sistemas-operacionais/fedora/como-atualizar-o-grub-no-fedora.html]
- [https://askubuntu.com/questions/503766/change-plymouth-screen-resolution]
