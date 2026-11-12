# O Futuro do Estudo: Avatar CGI e Produtividade com IA

Producao audiovisual educacional curta combinando sintese de roteiro via LLM, geracao de personagem hiper-realista e sincronia labial (lip-sync) com avatar digital gerado por Inteligencia Artificial.

## Visao geral

Este projeto foi desenvolvido como solucao do laboratorio **"Natty or Not"** da DIO, explorando a convergencia de multiplas ferramentas generativas de IA para a criacao de conteudos didaticos imersivos.

No video produzido, um avatar digital fotorrealista apresenta de forma direta como a Inteligencia Artificial pode atuar como mentora e assistente de produtividade no cotidiano de estudantes de tecnologia, acelerando a sintese de documentacoes tecnicas e a estruturacao de cronogramas de aprendizado.

## Tecnologias e Ferramentas

| Etapa de Producao | Tecnologia | Finalidade |
|---|---|---|
| Roteirizacao e Copywriting | LLMs (ChatGPT / Gemini) | Estruturacao do roteiro conciso e objetivo |
| Geracao Visual do Avatar | IA Generativa de Imagem | Criacao do personagem 3D fotorrealista com iluminacao controlada |
| Voz Sintetica e Lip-Sync | Plataformas de Animacao e Voz | Sintese de audio vocal e sincronizacao labial automatica com o video |

## Processo de Criacao

1. **Concepcao e Roteirizacao:** Criacao de uma mensagem de alto impacto, sintetizada em poucos segundos para prender a atencao do espectador: *"A inteligencia artificial facilita sua vida. Ela resume artigos e cria cronogramas. E o seu assistente 24 horas. Estude de forma mais inteligente."*
2. **Engenharia de Prompt para Imagem:** Desenvolvimento de prompt focado em realismo fotografico, renderizacao detalhada de textura de pele, iluminacao volumetrica suave e expressao facial acolhedora.
3. **Animacao e Sincronizacao Labial:** Integracao da imagem estatica de alta definicao com a faixa de voz sintetizada, gerando os movimentos labiais, piscadas de olhos e microexpressoes naturais do personagem.

## Resultados e Acesso

O resultado final e um video fluido em formato vertical, pronto para consumo em plataformas digitais e demonstracao tecnica:

- **Arquivo de video local:** [`ia_generativa.mp4`](./ia_generativa.mp4)

Para reproduzir o video diretamente via terminal no Linux Mint:

```bash
# Execucao com mpv ou ffplay
mpv ia_generativa.mp4
# ou
ffplay -autoexit ia_generativa.mp4
```

## Decisoes tecnicas e Aprendizados

- **Encadeamento de pipelines de IA (Multimodalidade):** A criacao do artefato final exigiu a combinacao sequencial de tres modalidades distintas de inteligencia artificial (texto, imagem e audio/video), demonstrando a viabilidade de esteiras automatizadas de geracao de conteudo.
- **Aplicacao pratica no aprendizado continuo:** O experimento evidenciou o valor de modelos multimodais como aceleradores de estudo no suporte a sintese de documentacoes densas (como bancos de dados relacionais, SQL e arquiteturas de nuvem).
