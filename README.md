# AchôPreço

## Apresentação e objetivo
Ajudar compradores a consultar e comparar ofertas de lojas e marketplaces.

## Participação real e inteligência artificial
Daniel de Omena Loubaque é responsável pelos objetivos, decisões de produto e acompanhamento do projeto. Desenvolvimento e documentação contam com IA; não se afirma autoria manual exclusiva nem experiência formal como desenvolvedor contratado.

## Tecnologias utilizadas
TypeScript, React, Node.js, Vite, Cloudflare Workers, Drizzle ORM, Tailwind CSS. Tecnologias identificadas no projeto não equivalem a domínio avançado individual.

## Arquitetura
Interface React → Worker Cloudflare → serviços de catálogo e persistência; scripts Node.js para processamento e validação.

## Funcionalidades
Catálogo, busca e filtros; guias de compra; rotinas de reconciliação; integração de ofertas com Whapi.

## Demonstração
https://www.xn--achopreo-y0a.com.br/

## Capturas de tela
As capturas devem mostrar páginas públicas, sem sessões, tokens ou dados de terceiros. Consulte as imagens reais disponíveis no pacote do portfólio; nenhuma imagem sintética é apresentada como captura.

## Instalação
Este repositório é um estudo de caso, sem código operacional. No projeto privado: Node.js >=22.13, pnpm; pnpm install e pnpm dev, com configuração privada de ambiente. Não executar deploy ou migrações durante avaliação de portfólio.

## Testes e limites de validação
No projeto privado, há scripts tests/shopee-reconciliation.mjs e tests/whapi-publisher.mjs. Não executados nesta fase de documentação.

## Desafios técnicos
Manter catálogo consistente e impedir publicação de ofertas sem evidência suficiente.

## Soluções implementadas
Existem testes de reconciliação, retenção de catálogo e publicador Whapi no código privado. A existência dos testes não comprova execução recente nem operação atual dos agendamentos.

## Próximas melhorias
Revalidar atualização de catálogo, comparação de produtos e agendamentos; acompanhar integridade dos links.

## Segurança
Este documento foi escrito para publicação, sem copiar histórico, credenciais ou dados comerciais privados. Os originais privados permanecem privados. Auditoria documental em 14/11/2026; não constitui garantia de ausência de vulnerabilidades.

## Contato
[Daniel no GitHub](https://github.com/Danielloubaque) · [LinkedIn](https://www.linkedin.com/in/daniel-loubaque-58443a240/) · [Vyntriva Tech](https://vyntriva-tech.bakedcharm.chatgpt.site)
