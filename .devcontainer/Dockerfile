FROM mcr.microsoft.com/dotnet/sdk:6.0

# Run Update
RUN apt-get update -y 

# Install NodeJS and NPM
RUN apt-get install -y curl \
    && curl -sL https://deb.nodesource.com/setup_14.x | bash - \
    && apt-get install -y nodejs

# Install Typescript
RUN npm install -g typescript

# Install Powerapp CLI 
RUN apt-get install -y unzip \
    && apt-get install -y wget \
    && wget https://www.nuget.org/api/v2/package/Microsoft.PowerApps.CLI.Core.linux-x64 -P /tmp/ \
    && unzip /tmp/Microsoft.PowerApps.CLI.Core.linux-x64 -d /tmp/pac/ \
    && cp /tmp/pac/tools/. /usr/local/share/pac -r \
    && ln -s /usr/local/share/pac/pac /usr/local/bin/pac \
    && chmod u+x /usr/local/bin/pac
