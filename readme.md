# Tutorial básico
- Crie um arquivo .desktop e preencha esses campos abaixo:
```
[Desktop Entry]
Name=Postman
Exec=/home/igor/Programas/Postman/Postman
Terminal=false
Type=Application
Icon=/home/igor/Programas/Postman/resources/app/assets/icon.png
```
- Depois de criado execute no terminal:
```
$sudo desktop-file-install nome-do-arquivo.desktop
```