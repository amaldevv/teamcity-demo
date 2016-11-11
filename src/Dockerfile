FROM microsoft/dotnet

COPY . /app

WORKDIR /app

ENV ASPNETCORE_URLS = "http://*:8087"

EXPOSE  8087

ENTRYPOINT dotnet src.dll