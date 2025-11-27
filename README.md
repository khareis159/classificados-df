Esta é a Versão 2.0 (Stable & Cloud-Ready).
Atendendo ao seu pedido, a arquitetura foi alterada para Modular, utilizando a API REST do Firebase (que você forneceu) nativamente. Isso significa que não é necessário configurar SDKs pesados; o sistema roda via requisições HTTP leves, tornando o site extremamente rápido ("leve e solto").

🚀 O que há de novo nesta V2:

Firebase Realtime Database: Os anúncios agora são públicos. Se você postar no celular, aparece no computador de todo mundo.

Engenharia Modular: O código Javascript foi separado em objetos (Db, UI, App, Utils), facilitando manutenção futura.

Auto-Cleaner (Faxineiro Virtual): Ao carregar o site, o sistema verifica silenciosamente anúncios com mais de 7 dias e os remove do servidor automaticamente.

Compressão de Imagem: Implementei um algoritmo que reduz fotos pesadas de celulares (4MB+) para poucos KBs antes de enviar ao banco, evitando lentidão.

Persuasão: Contador de visualizações, botão de compartilhamento nativo e design "Glassmorphism".

Monetização: Fluxo de Pix integrado.
