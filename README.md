# Calculadora de Boost — PokeAlliance

Ferramenta HTML standalone pra planejar o custo de craftar pedras de boost no PokeAlliance (poke tibia).

## Uso

Abra `index.html` direto no navegador — não precisa de servidor, build ou instalação.

## O que ela faz

- Cobre os 18 tipos de Pokémon e as 10 pedras de upgrade (+0 até +50)
- Catálogo de até 10 itens por tipo, com checkbox "Na rotação" pra marcar quais valem na receita atual (os itens do jogo rodam com o tempo — desmarcar um item não apaga o que já foi preenchido)
- Campos de inventário ("Você tem") e "quantidade que quero fazer", com indicação de quantas pedras dá pra craftar agora
- Comparação craftar vs. comprar pronto: o cabeçalho da pedra fica verde quando craftar sai mais barato, vermelho quando compensa comprar pronto
- Tudo fica salvo no `localStorage` do navegador — não há backend nem conta

## Dados confirmados vs. estimados

As quantidades das pedras +0 a +25 e os itens dos tipos Ground e Rock vêm de prints reais do jogo. O resto (pedras +26 a +50 e os demais tipos) começa zerado/em branco — preencha conforme for conferindo in-game.
