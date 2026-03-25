# ---- Build stage ----
FROM node:22-alpine AS build

WORKDIR /app

COPY package*.json ./
RUN npm ci --omit=dev

COPY . .

# ---- Runtime stage ----
FROM dhi.io/node:22

WORKDIR /app

COPY --from=build /app /app

ENV NODE_ENV=production

EXPOSE 3000

CMD ["node", "server.js"]