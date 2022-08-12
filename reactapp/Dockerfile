FROM jarredsumner/bun:edge
WORKDIR /app
COPY . .
RUN bun install
EXPOSE 8080
ENTRYPOINT ["bun",  "dev", "-p", "8080"]
