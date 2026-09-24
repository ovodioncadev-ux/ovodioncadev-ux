# Ovo di Onça

**Ovo di Onça, o único caipira com a origem no nome.**

Onça de Pitangui já foi a terra do ouro. Hoje carregamos nossas raízes nos ovos.

---

## Quem somos

A Ovo di Onça é um negócio de família nascido em Onça de Pitangui, em Minas Gerais — a
antiga terra do ouro que dá nome à marca. Vendemos ovos caipiras por assinatura, com
entrega em casa em bairros de Belo Horizonte.

Este perfil guarda o código do que a gente usa para atender o cliente: o site onde a
pessoa escolhe o plano e o sistema interno que controla as entregas.

## Projetos

| Projeto | O que faz | Situação |
|---|---|---|
| **Site de assinatura** | Apresenta a história, os planos, os bairros atendidos e leva o pedido até o WhatsApp | No ar |
| **App de gestão** | Controle interno das assinaturas: plano, bairro, dia de entrega e status do cliente | Em desenvolvimento |

## Stack

React 19 · TypeScript · Vite 6 · Tailwind CSS 4 · lucide-react

Front-end em SPA, sem framework de estado: os dados de negócio (planos, bairros, FAQ)
ficam centralizados em `src/data/` e chegam aos componentes por props.

## Como a gente escreve código

Todo repositório aqui segue o `design.md` da marca. Em resumo:

- **Segredos só no `.env`.** Chave de API, token e senha nunca entram no Git. O `.env`
  está no `.gitignore` e nenhuma variável secreta usa o prefixo `VITE_`.
- **Nada de dado inventado.** Sem depoimento fake, sem nota, sem contador de clientes,
  sem selo sem lastro. Se o número não existe de verdade, ele não aparece na tela.
- **Duas fontes.** Aclonica em `h1` e `h2`, Poppins no resto.
- **Cor só por token.** A paleta vive em variáveis CSS; hex solto no componente não passa.
- **Texto com fato dentro.** Preço, prazo, bairro e forma de pagamento no lugar de adjetivo.
- **Contraste WCAG AA**, área de toque de 44×44px, navegação completa por teclado e
  layout testado em 360px, 768px e 1120px.
- **Movimento contido.** Acordeão e modal, nada de seção aparecendo na rolagem.

## Contato

Assinatura, dúvida sobre bairro atendido ou dia de entrega: fale com a gente no WhatsApp.

<!-- Confirme o número antes de publicar: WhatsApp (31) 0000-0000 -->
