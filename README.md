# ScriptsLinux-Fedora 40 Workstation

### Script Plymouth

1. Adicionar tema no caminho -> ***/usr/share/plymouth/themes***
2. sudo dnf install plymouth-plugin-script (Caso não tenha plymouth-plugin)
3. sudo plymouth-set-default-theme -R {***NOME DO TEMA***}

- Obs: Comando para saber tema atual: ***cat /etc/plymouth/plymouthd.conf*** 

### Atualizar GRUB 

- sudo grub2-mkconfig -o /boot/grub2/grub.cfg

# Fontes

- [https://diolinux.com.br/sistemas-operacionais/fedora/como-atualizar-o-grub-no-fedora.html]
- Temas Plymouth: [https://www.gnome-look.org/browse?cat=108&tag=boot]
