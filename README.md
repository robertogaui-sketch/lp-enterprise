# LP Enterprise — protótipo

Landing page de **Enterprise**: a escola falando com a família, para uso na
campanha de matrículas, com CTA de WhatsApp para o comercial da escola.

**Página:** https://robertogaui-sketch.github.io/lp-enterprise/

## O que é

Mesmo molde da LP de material (ACTA / Sant'Anna), com o conteúdo trocado de
material didático próprio para o **ecossistema da plataforma**: espaço do aluno,
formatos de estudo, acompanhamento da família, inclusão, uso seguro de IA e
secretaria.

Nasceu de uma dor real: escolas que não sabem o que contrataram — uma delas não
sabia que os alunos acessam a plataforma. A página precisa ser ampla o bastante
para o gestor descobrir o que tem, e leve o bastante para a família ler.

## Seções

1. **Hero** — a promessa, com o relatório do aluno
2. **Um sistema só** — a aula gera o dado, que vira estudo, que chega corrigido à família
3. **Formatos de estudo** — mapa mental, quiz, slides, vídeo, flashcards, jogos, tutor
4. **A família acompanha** — histórico de atividades e habilidades da BNCC
5. **Inclusão** — o perfil do aluno vale para toda prova e atividade
6. **IA com regra clara** — tutor que devolve a pergunta, anticola, e o que a família vê
7. **Nos bastidores** — matrícula/rematrícula e grade horária
8. **Teachy** — 81% / 86% / 96% + Stanford + HolonIQ
9. **Matrícula** — WhatsApp e Instagram da escola

## Fora do escopo

Studio, material didático próprio, ERP e gestão financeira — os dois últimos por
estarem em construção, sem data.

## Notas

- `lp-material.css` é cópia do template de material do repo `landing-pages`, sem
  alteração. A camada `.ent-*` no `<style>` do `index.html` tem só o que não
  existe no template.
- As imagens em `img/` vêm de `public/rede-acqua/img/` do mesmo repo.
- Hoje está com a paleta azul de fallback e textos de "Escola Demo". Vestir por
  escola é sobrescrever as variáveis `--lpm-*` na raiz `.lpm`.
- Se for para produção, o caminho é virar componente config-driven como
  `LpMaterial`, em `/escola/<slug>`.
