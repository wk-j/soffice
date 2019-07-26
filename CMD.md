```bash
docker-compose up

wget https://github.com/sbraconnier/jodconverter/releases/download/v4.2.2/jodconverter-cli-4.2.2.zip
unzip jodconverter-cli-4.2.2.zip

./jodconverter-cli-4.2.2/bin/jodconverter-cli \
    --timeout 999999
    --connection-url http://localhost:8100  \
    resource/chenz.docx a.pdf

./jodconverter-cli-4.2.2/bin/jodconverter-cli \
    --timeout 999999 \
    --connection-url http://localhost:8100  \
    resource/demo.docx a.pdf
```

