# brauser
<a href="https://github.com/Luapree/brauser/actions/workflows/pages/pages-build-deployment/"><img src="https://github.com/Luapree/brauser/actions/workflows/pages/pages-build-deployment/badge.svg" alt="compilar"></a><br>
<a href="https://discord.gg/yManCTBmq"><img alt="Discord" src="https://img.shields.io/discord/1512139882829582347"></a>
</p>

brauser is a custom lightweight homepage intended for devices not intended to browse the internet<br>

### Running locally
#### Python
You can host brauser simply by using python

    python -m http.server

#### Docker
You can also use the included dockerfile<br>

Build:<br>

`docker build -t brauser .`

Run:<br>

`docker run -d --name brauser -P brauser`

## Lisence

[MIT Lisence](https://github.com/Luapree/brauser/blob/main/LICENSE)