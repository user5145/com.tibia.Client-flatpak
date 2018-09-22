# com.tibia.Client-flatpak
flatpak wrapper for Tibia's client

## Build & Install
### Repo

    flatpak-builder --force-clean builds --repo=/home/$USER/.local-repo com.tibia.Client.yml
    flatpak --user install local-repo com.tibia.Client

### Direct

    flatpak-builder --user --force-clean --install builds com.tibia.Client.yml
    
### Add a repository

    flatpak --user remote-add --no-gpg-verify --if-not-exists local-repo /home/$USER/.local-repo

It uses Maknus Dave's icon from www.deviantart.com/maknusdave/art/TIBIA-ICON-322439278
