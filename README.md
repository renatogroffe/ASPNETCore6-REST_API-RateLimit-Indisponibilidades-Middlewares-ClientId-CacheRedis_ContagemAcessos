# ASPNETCore6-REST_API-RateLimit-Indisponibilidades-Middlewares-ClientId-CacheRedis_ContagemAcessos
Exemplo de API REST para contagem de acessos criada com .NET 6 + ASP.NET Core e que faz uso do projeto AspNetCoreRateLimit + cache distribuído com Redis para testes de Rate Limit (com um Header de Subscription/Client Id) e uso de checagens de indisponibilidade da aplicação (middleware).

Lembrando que middlewares no ASP.NET Core são uma variação do pattern Chain of Responsibility. Maiores informações sobre este padrão em:

**https://en.wikipedia.org/wiki/Chain-of-responsibility_pattern**
