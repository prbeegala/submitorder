FROM mcr.microsoft.com/azure-functions/dotnet:3.0.13614-appservice

ENV AzureWebJobsStorage DefaultEndpointsProtocol=https;AccountName=sakflogicapps;AccountKey=nYwdRSAfDIgbG/MfRuMIqt2tZmc9rxYONbT2zU/DI6ZfM7j0wFkmA1yJODUsBnxy72K7m87jnjLAOHyeaNBTtg==;EndpointSuffix=core.windows.net

ENV AzureWebJobsScriptRoot=/home/site/wwwroot \ AzureFunctionsJobHost__Logging__Console__IsEnabled=true

COPY . /home/site/wwwroot