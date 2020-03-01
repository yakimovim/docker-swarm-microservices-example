FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-buster-slim

COPY ./bin/Debug/netcoreapp3.1/publish /app/

WORKDIR /app

EXPOSE 80

ENTRYPOINT ["dotnet", "Frontend.dll"]