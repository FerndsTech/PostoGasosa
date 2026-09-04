# 00 — Guia de Campo: Levantamento no Posto (São José do Belmonte/PE)

> **Objetivo:** coletar em UMA visita tudo o que a pesquisa precisa para fechar a arquitetura.
> A cadeia que precisamos desvendar é: **marca → modelo → controlador → protocolo**.
> **Como usar:** leve no celular, marque os itens, preencha a tabela do final e traga as fotos + respostas de volta.

Data da visita: ____/____/2026  |  Preenchido por: ______________

---

## 1. Fotos a tirar

### Placa de preços (a da entrada, vista da rua)
- [ ] Foto frontal completa (de longe, como o cliente vê da estrada)
- [ ] Foto de perto de uma linha de preço (dígitos, vírgula, cor dos LEDs)
- [ ] Quantas linhas de preço? ( ) gasolina comum ( ) aditivada ( ) etanol ( ) diesel S10 ( ) S500 ( ) GNV ( ) outra: ____
- [ ] Fotos do verso/interior da placa, se acessível com segurança
- [ ] Toda etiqueta, adesivo, serial ou selo que aparecer (em qualquer peça!)

### Central / controlador (a caixa que comanda a placa)
- [ ] Foto da caixa fechada + do lugar onde está instalada
- [ ] Foto da etiqueta de marca/modelo (lateral, traseira ou dentro da tampa)
- [ ] Foto de TODAS as conexões: cabos que entram/saem, conectores (DB9/serial? borne de parafusos? RJ45/rede? antena?)
- [ ] Se puder abrir COM SEGURANÇA (desligada): foto da placa eletrônica dos dois lados — chips principais e conectores
- [ ] LEDs de status da central (acesos/piscando? cores?)

### Controle remoto (se existir)
- [ ] Foto do controle: botões, etiquetas, tela (se tiver)
- [ ] Assistir o funcionário trocar um preço e anotar o passo a passo

### Infraestrutura
- [ ] Roteador/modem/central de internet do posto (se houver)
- [ ] Quadro de energia mais próximo da placa/central
- [ ] Estimar a distância: central da placa ↔ escritório/roteador (____ metros; paredes/obstáculos no caminho?)

---

## 2. Perguntas ao dono / gerente

### Negócio
1. Quantos postos você tem? Em quais cidades?
2. Tem bandeira (branca, Ipiranga, Shell, Petrobras...)? — *importa por causa de padrão visual e regras da distribuidora*
3. Quem troca os preços hoje e COMO? ( ) faixas de vinil ( ) números manuais ( ) controle remoto ( ) empresa contratada
4. Com que frequência o preço muda? ( ) por semana ( ) por mês ( ) raramente
5. Quanto custa hoje uma troca de preço? (material + mão de obra + andaime + tempo parado)
6. Já aconteceu da placa estar com preço diferente da bomba? O que aconteceu?
7. Se pudesse trocar o preço do celular em 30 segundos, o que mudaria na operação?
8. Além de você, quem precisaria de acesso ao sistema? (gerente? frentista só consultando?)
9. Quanto investiria num piloto? E quanto por mês valeria o serviço depois de funcionando?

### Infra (crítico no sertão)
10. Tem internet no posto? Qual tipo (Wi-Fi de fibra / modem 4G / nenhum)? Operadora?
11. Sinal de celular no local: testar na hora — qual operadora pega melhor? ( ) Vivo ( ) Tim ( ) Claro ( ) Oi
12. A energia cai com frequência? Quanto tempo fica fora? Tem gerador/nobreak?
13. Onde poderia ficar a "caixinha" do gateway (perto da central da placa)? Tem tomada perto?

### Técnico / histórico
14. A placa é LED eletrônica ou números trocados manualmente?
15. Quem fabricou/instalou o painel? Ainda tem contato do fornecedor/técnico local?
16. Existe automação das bombas (concentrador, telemetria)? Qual sistema?
17. A placa tem quantos anos? Já deu problema? Quem consertou?

---

## 3. Segurança na visita

- **NÃO abrir caixas energizadas.** Se precisar ver dentro, pedir para desligar no disjuntor E confirmar com alguém responsável.
- **NÃO desligar a placa de preços sem avisar** — é um ambiente operacional.
- Fotos de etiquetas geralmente bastam; não desmontar nada.
- Atenção a choque: painéis têm fonte 110/220V e placas antigas podem ter neon (alta tensão).

---

## 4. Tabela de respostas

| # | Resposta curta | Observações |
|---|---|---|
| 1-9 (negócio) | | |
| 10-13 (infra) | | |
| 14-17 (técnico) | | |

---

## 5. Depois da visita

Traga para o agente: **(a)** todas as fotos, **(b)** a tabela preenchida, **(c)** qualquer observação solta.
Com marca + modelo do controlador em mãos, a pesquisa sai do genérico e vai direto ao protocolo específico — e aí fechamos o desenho do gateway.
