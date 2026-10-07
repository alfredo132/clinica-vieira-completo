# Clínica Odonto Teste

Site de demonstração da Clínica Vieira, clínica odontológica fictícia na Savassi, em Belo Horizonte.

- `index.html`: página principal, com tratamentos e preço inicial, antes e depois, carta da fundadora, equipe, convênios e pagamento, avaliações no formato do Google, endereço com galeria de fotos da clínica e agendamento que monta a mensagem e abre o WhatsApp
- `equipe.html`: perfil de cada dentista, com CRO, formação, cursos e diplomas
- `styles.css`: visual compartilhado pelas duas páginas

Para usar com uma clínica real:

1. Troque o número em `WHATSAPP` nos dois arquivos HTML.
2. Troque nome, endereço, telefone, convênios, preços, nota do Google e fotos.
3. Em `index.html`, edite as listas `TREATMENTS`, `TEAM`, `REVIEWS` e `PHOTOS` (fotos da clínica que passam no fim da página).
4. Avaliações: use só avaliações reais da própria clínica. Salve os prints na pasta `avaliacoes/` e troque cada item de `REVIEWS` por `{ img: "avaliacoes/print-1.png", name: "Nome de quem avaliou" }`.
5. Em `equipe.html`, edite a lista `TEAM`. Para mostrar a foto de um diploma, salve a imagem na pasta `diplomas/` e preencha `img` no item.
