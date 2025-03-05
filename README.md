# comm-wmaker - Metapacote para WindowMaker com Automações e Aparência Retro

O **comm-wmaker** é um metapacote que facilita a instalação e configuração do **WindowMaker**, um gerenciador de janelas leve e altamente personalizável, com um toque retro inspirado na era clássica dos desktops. Este pacote inclui automações no menu de aplicativos, melhorias de usabilidade e uma aparência visual que remete aos anos 90, além de wallpapers exclusivos criados por inteligência artificial.

---

## Funcionalidades Principais

- **Automação no Menu de Aplicativos**: Quando você instala um novo aplicativo, ele é automaticamente categorizado no menu de aplicativos do WindowMaker.
- **Aparência Retro**: Temas e ícones que recriam a experiência visual clássica dos anos 90.
- **Wallpapers Exclusivos**: Papéis de parede gerados por inteligência artificial para complementar a aparência retro.
- **Integração com BigLinux**: Compatível com as ISOs **BigCommunity Base** e **Minimal**.

---

## Como Usar

### Pré-requisitos

- Ter instalado o **BigLinux** (Base ou Minimal).
- Conexão com a internet para instalação dos pacotes.

### Instalação

1. Atualize seu sistema:
   ```bash
   sudo pacman -Syu
   ```

2. Instale o metapacote `comm-wmaker`:
   ```bash
   sudo pacman -S comm-wmaker
   ```

3. Reinicie o sistema ou reinicie o gerenciador de exibição para aplicar as alterações.

---

## Pacotes Incluídos

O metapacote `comm-wmaker` instala os seguintes pacotes:

### Gerenciador de Janelas e Temas
- `windowmaker`
- `windowmaker-extra`
- `tango-icon-theme`
- `qt5ct`

### Gerenciamento de Sessão
- `lxdm`
- `lxdm-biglinux-theme`

### Ferramentas de Acessibilidade
- `numlockx`
- `onboard`
- `mousetweaks`

### Ferramentas de Sistema
- `polkit`
- `polkit-kde-agent`
- `autoconf`
- `imake`
- `dolphin`
- `rootactions-servicemenu-biglinux`
- `xterm`
- `konsole`
- `helvum`
- `kate`
- `kcalc`
- `xorg-fonts-cyrillic`
- `xorg-mkfontscale`
- `network-manager-applet`
- `wmclock`
- `wmsystemtray`
- `wmix`
- `wmmemload`
- `wmnd`
- `wmautomenu-biglinux`
- `lxrandr`
- `notification-daemon`
- `pamac-tray-icon-plasma`
- `ark`
- `xorg-xkill`
- `bluedevil`
- `manjaro-settings-manager`
- `gwenview`
- `spectacle`
- `clipit`
- `volumeicon`
- `hardinfo-gtk3`
- `okular`
- `xfce4-settings`
- `xfce4-appfinder`
- `xfce4-notifyd`
- `xfce4-taskmanager`
- `chili-utils`
- `noto-fonts-emoji`
- `grub-btrfs`
- `grub-btrfs-timeshift`
- `timeshift`
- `bash-completion`
- `firefox`
- `xfce4-terminal`
- `base-devel`
- `libx11`
- `libxext`
- `libxpm`
- `qt6-charts`
- `cbatticon`

---

## Personalização

Após a instalação, você pode personalizar o WindowMaker através do menu de configurações ou editando manualmente os arquivos de configuração localizados em `~/.GNUstep/`.

---

## Contribuição

Se você deseja contribuir para o desenvolvimento ou melhoria deste metapacote, sinta-se à vontade para abrir uma **issue** ou enviar um **pull request** no repositório oficial.

---

## Licença

Este projeto está licenciado sob a licença [GPL-3.0](LICENSE).

---

**Nota**: Este projeto é mantido pela comunidade e não possui afiliação oficial com o projeto WindowMaker ou BigLinux.
```

Grato
Rafael Ruscher 😊

   
