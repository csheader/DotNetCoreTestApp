FROM microsoft/aspnetcore:1.1.0
ENTRYPOINT ["dotnet", "DockerTestApplication.dll"]
ARG source=.
WORKDIR /app
ENV ASPNETCORE_URLS http://*:80
EXPOSE 80
COPY out /usr/local
