FROM mcr.microsoft.com/dotnet/aspnet:5.0
LABEL version="1.0.1" description="Aplicacao ASP .NET CORE Web API "
COPY dist /app
WORKDIR /app
EXPOSE 80/tcp
ENTRYPOINT [ "dotnet", "webapi.dll" ]