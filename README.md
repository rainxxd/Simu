Prezados(as),

Ao realizar o clone, executar os seguintes comandos no terminal

## 💻 Rodando local
1) Restaurar pacotes:
```bash
dotnet restore
```
2) Rodar a API:
```bash
dotnet run --project Simulacao.Api
```
3) Swagger fica disponível em:
```bash
http://localhost:5000/swagger
```

## 🐳 Rodando com Docker
1) Suba o docker:
```bash
cd Simulacao.Api
docker-compose up --build
```
2) Swagger fica disponível em:
```bash
http://localhost:5000/swagger
```
