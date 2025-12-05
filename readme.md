# Keychat App

../flatpak-flutter.py flatpak-flutter.yml --from-git-branch flatapp --app-module keychat-app


sudo HTTPS_PROXY="http://127.0.0.1:7890" HTTP_PROXY="http://127.0.0.1:7890" flatpak-builder --repo=repo --user --force-clean --sandbox --install --install-deps-from=flathub --arch=x86_64 build com.keychat.io.yml 