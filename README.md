
# Telessaúde Missionária - assistente medico

**Telessaúde Missionária** é uma ferramenta web de apoio à saúde e triagem para missionários, voluntários, famílias e comunidades em campo, especialmente em contextos com acesso limitado a médicos.
O app utiliza inteligência artificial para gerar relatórios e orientações claras, em linguagem simples, para adultos e crianças, sem substituir o cuidado médico humano.

## Funcionalidades

* **Triagem de Sintomas (Adulto e Pediátrico/Kids):**

  * Preencha um questionário simplificado e receba orientação baseada em IA, incluindo folheto educativo personalizado.
  * Análise detalhada dos sintomas, fatores de risco e sinais de alerta.
* **Assistente Médico IA:**

  * Faça perguntas livres (ex: “Quais sintomas de dengue?”) e receba respostas em linguagem leiga.
* **Triagem de Emergência:**

  * Guia visual para níveis de urgência, ajudando a identificar situações que exigem atendimento imediato.
* **Geração de Relatório:**

  * Salve ou compartilhe seu relatório em PDF ou diretamente pelo WhatsApp.
* **Modo PWA (Aplicativo Instalável):**

  * Instale o app na tela inicial do Android ou iOS e use também offline.
* **Privacidade:**

  * Nenhum dado sensível é armazenado em servidor ou compartilhado com terceiros por padrão.

## Como usar

1. **Acesse o app pelo navegador**
   Exemplo: [https://telesaudemissionaria.github.io/telemissao/](https://telesaudemissionaria.github.io/telemissao/)
2. Clique em **Iniciar Avaliação de Sintomas** e escolha Adulto ou Criança.
3. Preencha as perguntas e aguarde a análise.
4. Compartilhe o resultado pelo WhatsApp ou baixe em PDF.
5. Use o menu inferior para acessar o Assistente IA, Triagem de Emergência ou Ajuda.

## Instalação como App Android (PWA)

1. Abra o site no **Chrome do Android**.
2. Toque no menu (⋮) e escolha **“Adicionar à tela inicial”**.
3. O app funcionará como aplicativo nativo, até offline (quando possível).
4. Para iPhone/iPad, use o Safari e selecione **“Adicionar à Tela de Início”**.

> **Nota:** O app pode ser hospedado em qualquer serviço estático (GitHub Pages, Netlify, Vercel etc.)
> Para publicar na Play Store, utilize o [PWABuilder](https://www.pwabuilder.com/).

## Estrutura dos Arquivos

* `index.html` – Código principal do aplicativo.
* `manifest.json` – Configurações do app PWA (ícones, nome, cor etc).
* `icon-192.png`, `icon-512.png` – Ícones para app e splash screen.
* `sw.js` – (Opcional) Service Worker para funcionamento offline.
* Demais imagens, scripts ou arquivos de estilo podem ser adicionados conforme necessidade.

## Segurança e Privacidade

* **Atenção:** Este aplicativo é um auxiliar educativo e NÃO substitui avaliação médica profissional.
* Em caso de sintomas graves, procure imediatamente um serviço de saúde.
* Leia a [Política de Privacidade](./POLITICA_DE_PRIVACIDADE.md) para mais detalhes.

## Contribuição

* Feedbacks, sugestões e melhorias são bem-vindos!
* Para contribuir, abra um pull request ou envie sugestões para [missionarymedicalcare@gmail.com](mailto:missionarymedicalcare@gmail.com)

## Licença

Projeto aberto sob licença MIT.
Veja o arquivo [LICENSE](./LICENSE) para detalhes.

---

> “A Telessaúde Missionária existe para apoiar, e não substituir, o cuidado humano.”
> — Equipe Telessaúde Missionária

---

