# 1. vytvořit image z alpine
FROM alpine

WORKDIR /src

# 2. nakopírovat main.sh
COPY main.sh /src

# 3. říct image, jak se spustit
#CMD ["ls", "/", "/watch"]
CMD ["/src/main.sh"]

# 4. build image
# 5. spustit image s namountovaným souborem file.txt do /home/folder-mapping/file.txt
