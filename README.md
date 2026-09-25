# Manual de Manutenção Básica de Bicicleta

Site estático em HTML puro (sem CSS) com cuidados básicos de manutenção para
três tipos de bicicleta: urbana, mountain bike e speed. Feito como projeto de
estudo de HTML semântico.

## Como abrir

Basta abrir `html/index.html` em qualquer navegador. Os links de navegação
levam para as outras páginas dentro da mesma pasta `html/`.

## Estrutura de pastas

```
.
├── README.md
├── html/
│   ├── index.html        → página inicial, apresentação do projeto
│   ├── tipos.html        → tabela comparativa e descrição dos 3 tipos de bike
│   ├── manutencao.html   → FAQ, checklist e formulário de agendamento de revisão
│   ├── galeria.html      → galeria de imagens, áudio e vídeo
│   └── contato.html      → formulário de contato
├── img/                  → fotos usadas nas páginas
├── audio/                → arquivo de áudio (dica sobre cuidados com a bike)
└── video/                → arquivo de vídeo (oficina de bikes em casa)
```

## Páginas

- **index.html** — apresentação do manual, explica o objetivo do projeto e traz
  uma citação sobre HTML semântico.
- **tipos.html** — tabela comparativa (com bordas visíveis via `border="1"`)
  com uso ideal e pressão de pneu recomendada para cada tipo de bike, seguida
  de uma descrição de cada uma (urbana, mountain bike e speed), cada uma com
  sua própria foto.
- **manutencao.html** — FAQ, checklist de manutenção e formulário de
  agendamento de revisão.
- **galeria.html** — galeria de fotos, um áudio com dicas e um vídeo sobre
  como montar uma oficina de bikes em casa.
- **contato.html** — formulário de contato.

## Sobre as imagens, o áudio e o vídeo

As fotos em `img/` foram enviadas pelo autor do projeto: bicicleta híbrida
(banner), bicicleta urbana, kit de ferramentas, mountain bike em trilha,
manutenção em garagem e bicicleta speed. O áudio "5 dicas pra cuidar bem da
bike" e o vídeo "Quer começar uma oficina de bikes na garagem de casa?" são
do canal **Pedaleria**, usados aqui como material de apoio — créditos
detalhados dentro de `galeria.html`.

## Requisitos atendidos

- 5 páginas HTML com navegação (menu) idêntica em todas elas.
- Estrutura semântica completa: `header`, `nav`, `main`, `section`, `article`,
  `aside` e `footer` em todas as páginas.
- Tabela 3×3 com `colspan` em `tipos.html`, com bordas via `border="1"`.
- Formulário avançado (`type="date"`, `type="range"`, `type="file"`,
  `datalist`, `required`, `placeholder`) em `manutencao.html`, com formulário
  de contato adicional em `contato.html`.
- `details`/`summary` em `manutencao.html` e `galeria.html`.
- `figure`/`figcaption` em `index.html`, `tipos.html` (bicicleta urbana,
  mountain bike e speed) e `galeria.html`.
- Marcação avançada (`abbr`, `mark`, `del`, `ins`, `blockquote`, `cite`,
  `progress`, `meter`) distribuída pelas páginas.
- Áudio e vídeo locais reais em `galeria.html`.
- Sem CSS (`style=`, `<style>`, `<center>`, `cellpadding` ou `align`) — o
  único ajuste visual usado é o atributo HTML `border` na tabela.

### Requisitos de autoria

- `<time datetime="2026-09-25">` com a data da prova, em `index.html`.
- `blockquote` com frase do professor sobre HTML, em `index.html`.
- Comentário HTML explicando uma dificuldade real (o vídeo recebido é o
  material completo de quase 18 minutos, sem um editor disponível para
  cortar só o trecho relevante), em `galeria.html`.
