# Keychat App

../flatpak-flutter/flatpak-flutter.py flatpak-flutter.yml --from-git-branch main --app-module keychat-app

sudo flatpak-builder --repo=repo --force-clean --sandbox --install --install-deps-from=flathub build com.keychat.io.yml 

-- HTTPS_PROXY="http://127.0.0.1:7890" HTTP_PROXY="http://127.0.0.1:7890" 