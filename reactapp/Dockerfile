FROM jarredsumner/bun:edge
COPY . .
RUN bun install
EXPOSE 8080
ENTRYPOINT ["bun",  "dev", "-p", "8080"]