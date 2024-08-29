https://chocolatey.org/install

https://community.chocolatey.org/packages

install/use needs elevated terminal.

```pwsh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```


```pwsh
choco install -y dotnet-sdk
choco install -y vscode
choco install -y azure-cli
choco install -y powershell-core
choco install -y git
```

```pwsh
Import-Module "$env:ChocolateyInstall\helpers\chocolateyProfile.psm1"
refreshenv
```
