FROM node:10.13-alpine
WORKDIR /app
RUN npm install -g npm \
        create-nuxt-app \
        ionic cordova \
        @vue/cli \
        @vue/cli-service-global
RUN npm install -save nuxt \
        axios
CMD ["sh"]
