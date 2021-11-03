# Running a Container on Azure App Service
This file contains the URLs and Dockerfile text needed for the demo in Cloud Academy's _Running a Container on Azure App Service_ course.  

### Free Azure Trial
https://azure.microsoft.com/free  

### Docker Download
https://docs.docker.com/get-docker

### Visual Studio Code Download
https://code.visualstudio.com

### Dockerfile
```
FROM mcr.microsoft.com/appsvc/dotnetcore:lts

ENV PORT 8080
EXPOSE 8080

ENV ASPNETCORE_URLS "http://*:${PORT}"

ENTRYPOINT ["dotnet", "/defaulthome/hostingstart/hostingstart.dll"]
```

### Support
support@cloudacademy.com
