# Clínica Odonto Teste

Site de demonstração da Clínica Vieira, clínica odontológica fictícia na Savassi, em Belo Horizonte.

- `index.html`: página principal, com tratamentos em mosaico de fotos (duração e número de consultas), 3 casos de antes e depois para arrastar, três promessas da clínica com assinatura da fundadora, equipe, convênios, avaliações no formato do Google, endereço com galeria de fotos da clínica e agendamento que monta a mensagem e abre o WhatsApp
- `equipe.html`: perfil de cada dentista, com CRO, formação, cursos e diplomas
- `styles.css`: visual compartilhado pelas duas páginas

Para usar com uma clínica real:

1. Troque o número em `WHATSAPP` nos dois arquivos HTML.
2. Troque nome, endereço, telefone, convênios, nota do Google e fotos. A foto da capa fica em `images/capa.webp`.
   Não coloque preços, "avaliação gratuita" nem formas de pagamento: o Código de Ética Odontológica proíbe anunciar isso.
3. Em `index.html`, edite as listas `TREATMENTS`, `TEAM`, `REVIEWS` e `PHOTOS` (fotos da clínica que passam no fim da página).
4. Avaliações: use só avaliações reais da própria clínica. Salve os prints na pasta `avaliacoes/` e troque cada item de `REVIEWS` por `{ img: "avaliacoes/print-1.png", name: "Nome de quem avaliou" }`.
5. Antes e depois: use só casos reais da clínica, com autorização por escrito do paciente. Salve as fotos em `antes-depois/` e troque cada item de `CASES` por `{ before: "antes-depois/caso1-antes.jpg", after: "antes-depois/caso1-depois.jpg" }`.
6. Em `equipe.html`, edite a lista `TEAM`. Para mostrar a foto de um diploma, salve a imagem na pasta `diplomas/` e preencha `img` no item.

Temas de cor (mesmo layout, só cores e fontes):

- original: azul e Archivo
- `?tema=salvia`: verde-sálvia e creme, títulos serifados (`tema-salvia.css`)
- `?tema=champanhe`: preto, areia e detalhes dourados (`tema-champanhe.css`)

Os links entre as páginas levam o tema junto. Sem `?tema` aparece o original.
