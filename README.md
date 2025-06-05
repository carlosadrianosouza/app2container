Repositorio aplicacao que foi usada para migracao com App2Container AWS



## Necessario instalar dotnet-hosting-6.0.25-win com o comando abaixo:

RUN powershell -NoProfile -Command \
Invoke-WebRequest -Uri https://download.visualstudio.microsoft.com/download/pr/1fd87564-6bdb-4123-90dd-26488ec868c9/6c68988c310805bdcbb07b704fbe3e9d/dotnet-hosting-6.0.25-win.exe -OutFile dotnet-hosting-6.0.25-win.exe
.\dotnet-hosting-6.0.25-win.exe /install /q /restart
