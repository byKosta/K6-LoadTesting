<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://cdn.icon-icons.com/icons2/3912/PNG/512/k_logo_icon_247940.png" alt="Project logo"></a>
</p>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/byKosta/K6-LoadTesting.svg)](https://github.com/byKosta/K6-LoadTesting/pulls)
[![GitHub Issues](https://img.shields.io/github/issues/byKosta/K6-LoadTesting.svg)](https://github.com/byKosta/K6-LoadTesting/issues)
[![GitHub Stars](https://img.shields.io/github/stars/byKosta/K6-LoadTesting.svg)](https://github.com/byKosta/K6-LoadTesting/stargazers)

</div>

## Installation on Windows

There are several ways to install k6 on Windows:

If you use the Chocolatey package manager, you can install the unofficial k6 package as follows:

1. Install Chocolatey by running the following command in PowerShell:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

```
## Check the Chocolatey version:
```
choco -v
```
## Install k6:
```
choco install k6
```

## If you use the Windows Package Manager, install the official packages from the k6 manifests:
```
winget install k6 --source winget
```

For more information about k6, you can refer to the official k6 documentation. It provides comprehensive guides and API references to help you get started with k6.

https://k6.io/docs/

### Get started!

Test the K6 using the following command:

```
k6 run stages.js
```

## k6 API:

https://k6.io/docs/javascript-api/

Practice and learn the process of API 

https://test-api.k6.io



