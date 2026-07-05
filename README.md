# Análise de Infraestrutura Client-Side: SentinelSDK no ChatGPT

Análise voluntária e independente focada na auditoria de isolamento de variáveis em memória e mapeamento de telemetria do componente SentinelSDK da OpenAI.

---

## 📄 Relatório Técnico Completo

O write-up detalhado com a metodologia, análises de segurança, propostas de mitigação e o retorno oficial da equipe de segurança da OpenAI foi compilado em um documento oficial.

### 🔗 [Clique aqui para ler o Relatório Técnico (PDF)](./relatorio_sentinel.pdf)

---

### 🛠️ Escopo da Auditoria
* **Vulnerabilidade:** Vazamento de Escopo Global (Global Scope Leakage) via objeto `window`.
* **Componente:** SentinelSDK (`sdk.js` / `frame.html`).
* **Status:** Divulgação Responsável (*Responsible Disclosure*) enviada e encaminhada para a engenharia da OpenAI.

*Para ler o documento com toda a formatação original, códigos-fonte demonstrativos e imagens de evidência, acesse o link do PDF acima.*
