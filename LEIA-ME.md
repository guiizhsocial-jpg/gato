# Pedacinhos de Nós v2: o que enviar ao GitHub

Entre em Code > main e envie (Add file > Upload files):
1. `www/index.html` (dentro da pasta www, substitui o antigo)
2. A pasta `assets` (3 imagens do ícone)
3. `debug.keystore` (na raiz do repositório)
4. Abra `.github/workflows/main.yml`, apague tudo e cole o conteúdo de `build-apk.yml` deste zip.

Depois, em Actions, espere o check verde e baixe o pedacinhos-apk.
A PRIMEIRA instalação desta versão exige desinstalar o app antigo (a assinatura muda). Depois disso, os próximos APKs instalam por cima sem perder nada.
Para usar uma foto de vocês no ícone, troque `assets/icon-only.png` por uma imagem quadrada de 1024x1024.
