## NextJS-commands

# Installation

Version **20.3** worked on my Windows 10 laptop

`https://nodejs.org/download/release/v20.3.0/node-v20.3.0-win-x64.7z
`

Configuring paths and custom cache location

    SET PATH=%PATH%;F:\Apps\Dev\nodejs-20
    npm config set cache F:\Temp\NPM20-cache --global

Disable the telemetry

    npx next telemetry disable

Adding Node.exe to Firewall exception

    netsh advfirewall firewall add rule name="Node JS" dir=in action=allow program="f:\Apps\dev\nodejs-20\node.exe" enable=yes
