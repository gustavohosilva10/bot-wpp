
## Instalando as dependencias 

```bash
sudo apt install -y curl nano git gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget build-essential apt-transport-https libgbm-dev
```

```bash
cd ~
```

```bash
curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh
```

```bash
sudo bash nodesource_setup.sh
```

```bash
sudo apt -y install nodejs
```

```bash
node -v
```

```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

```bash
sudo apt install ./google-chrome-stable_current_amd64.deb
```

## Clonando e instalando meu próprio bot: 📚

```bash
git clone https://github.com/jhowbhz/bot-whatsapp.git
```

```bash
npm install --unsafe-perm
```

```bash
npm install -y pm2 -g
```

## Forma de usar: 💫
Depois de clonar instalar o projeto, basta digitar o seguinte, e ler o QR Code em seguida... 

```bash
npm start
```

Leu o QR Code? Tudo certo? Agora deixa ele rodando em background...

```bash
pm2 start index.js
```

```bash
pm2 startup
```





