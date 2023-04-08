# FROM node:lts AS runtime
# WORKDIR /app

# COPY . .

# # RUN npm install
# # RUN npm run build

# ENV HOST=0.0.0.0
# ENV PORT=3000
# EXPOSE 3000
# CMD node ./dist/server/entry.mjs

FROM node:16-alpine
WORKDIR /usr/src/app
COPY ./app /app
EXPOSE 3000