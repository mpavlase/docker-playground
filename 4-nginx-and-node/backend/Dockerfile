# 1. vytvořit image z node, tag si zvol podle sebe s odůvodněním
FROM node

# 2. nakopíruj správné soubory
WORKDIR /src

COPY . /src

# 3. nainstaluj závislosti
RUN ["yarn"]

# 4. urči entrypoint a cmd
CMD ["node", "app.js"]


# 5. build image
# 6. vytvoř síť typu bridge s názvem 'mydockernetwork'
# 7. spusť image, container má být na síti 'mydockernetwork'
