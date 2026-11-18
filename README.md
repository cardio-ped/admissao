# Admissão POI · UTI CardioPed IMIP

Ferramenta de apoio para a admissão de pacientes no pós-operatório imediato (POI) de cirurgia cardíaca pediátrica na UTI CardioPed do IMIP (Recife/PE).

Os dados do paciente são digitados **uma única vez**. A partir deles, o app monta e imprime:

- **Prescrição POI**: venóclise, correções de K e Ca e medicações. A faixa de peso é escolhida automaticamente (< 10 · 10 a < 20 · 20 a 40 · > 40 kg).
- **Folha de Parada Cardiorrespiratória**, nos modelos 1 e 2, com as doses calculadas pelo peso.
- **Controle da Pressão Arterial**: percentis P5–P95 de PAS, PAD e PAM, conforme o sexo e a idade.

Há duas formas de saída:

- **Imprimir**: abre a janela de impressão do navegador, que também permite “Salvar como PDF”.
- **Baixar PDF**: gera o arquivo diretamente.

## Privacidade

Nada do que é digitado é gravado ou enviado: o app roda inteiro no navegador, e os dados somem ao recarregar ou fechar a página.

## Aviso

Esta é uma ferramenta de apoio. Confira sempre as doses antes de prescrever.

---

Serviço de Cirurgia Cardiovascular Pediátrica · IMIP.

Créditos de terceiros:

- Fonte Archivo (SIL Open Font License).
- jsPDF e jsPDF-AutoTable (licença MIT).
- O modelo 2 da folha de parada é baseado no original © 2022 de Bárbara França e Sheyla Levy.
