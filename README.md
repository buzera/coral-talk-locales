# coral-talk-locales
Custom translations for Coral Talk commenting platform

Clone this repository, replace '/your/local/path/' with your git clone location and define the translations volume in your docker-compose.yml file:
```
services:
  talk:
    image: coralproject/talk:9
    restart: always
    volumes:
      - /your/local/path/locales:/usr/src/app/locales
    [...]
```
