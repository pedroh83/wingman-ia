# Wingman IA 💬
### Assistente de paquera para conversas naturais, confiantes e respeitosas

Wingman IA é um GPT personalizado que ajuda a interpretar mensagens recebidas em conversas de paquera e sugerir respostas curtas, espontâneas e alinhadas ao contexto. O objetivo é apoiar a comunicação — não manipular sentimentos nem tratar sinais ambíguos como prova de atração.

> **Status:** protótipo de GPT personalizado; não é um aplicativo independente.

## O que faz
- Analisa o tom da mensagem e o contexto informado.
- Explica brevemente o que é possível inferir — e o que não é.
- Sugere uma resposta principal e, quando útil, uma alternativa.
- Recomenda não insistir diante de desinteresse ou limite explícito.
- Ajuda com quebra-gelos e convites descontraídos, sem pressão.

## Exemplo
**Mensagem:** “Você é sempre assim ou está tentando me conquistar? 😂”

**Leitura:** tom brincalhão; pode ser uma abertura para flertar, mas não confirma interesse romântico.

**Sugestão:** “Ah, então você também gosta de me provocar? 😂”

## Como usar
1. Configure um GPT personalizado no ChatGPT.
2. Copie `docs/instrucoes-gpt.md` para o campo de instruções.
3. Se desejar, adicione exemplos e material de referência em Conhecimento.
4. Envie uma mensagem ou descreva o contexto. Oculte dados pessoais de terceiros em prints.

## Princípios
- Naturalidade antes de frases ensaiadas.
- Flerte leve, proporcional ao tom da conversa.
- Respeito à autonomia e aos limites da outra pessoa.
- Curtidas, emojis e respostas curtas não são provas de atração.
- Não prometer que uma mensagem “vai conquistar” alguém.

## Estrutura
```text
wingman-ia/
├── LICENSE
├── README.md
├── docs/
│   ├── instrucoes-gpt.md
│   └── guia-de-uso-e-privacidade.md
└── tests/
    └── casos-de-teste.md
```

## Limitações
Este repositório documenta instruções e testes de um GPT personalizado. Não envia mensagens por você nem acessa Instagram ou WhatsApp. A qualidade depende do contexto fornecido.

## Próximas melhorias
- [ ] Testar respostas com conversas fictícias variadas.
- [ ] Registrar feedback sobre naturalidade e adequação.
- [ ] Refinar instruções para evitar respostas longas ou artificiais.
- [ ] Considerar uma interface própria apenas se houver necessidade real.

## Licença
Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE) para mais detalhes.
