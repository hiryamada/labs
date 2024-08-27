https://chocolatey.org/install

```pwsh
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

https://community.chocolatey.org/packages

```pwsh
choco install -y dotnet-sdk
choco install -y vscode
choco install -y azure-cli
```
