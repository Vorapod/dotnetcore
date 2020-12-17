FROM mcr.microsoft.com/dotnet/aspnet:3.1
COPY bin/Release/netcoreapp3.1/publish/ NetCore.Docker/
WORKDIR /NetCore.Docker
ENTRYPOINT ["dotnet", "NetCore.Docker.dll"]