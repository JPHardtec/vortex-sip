# 🚀 Vortex SIP Softphone

![Version](https://img.shields.io/badge/version-v2.9.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20(x64)%20%7C%20Android-informational.svg)
![Edition](https://img.shields.io/badge/edition-FREE%20%2F%20PRO-success.svg)
![Author](https://img.shields.io/badge/desenvolvido%20por-Jean%20Palumbo%20%2F%20JPHardtec-blueviolet.svg)

**Vortex SIP Softphone** é um discador telefônico SIP corporativo de alta performance para Windows e Android, desenvolvido com motor nativo **PJSIP/PJSUA2 (C++)** e interface moderna em Dark Glassmorphism. Projetado para empresas, call centers, atendentes remotos e integradores de telefonia IP (VoIP/PABX Asterisk, FreePBX, Issabel, Elastix, 3CX, OpenSIPS, Kamailio).

---

## ⚡ Principais Recursos

- 🎧 **Qualidade de Áudio Cristalina**: Desenvolvido com motor nativo PJSIP em C++, garantindo baixíssima latência e suporte aos principais codecs VoIP (G.711 u-law/a-law, Opus, Speex).
- ⌨️ **Discagem DTMF por Teclado Físico na URA**: Digite facilmente as opções de menus de atendimento automático (URAs/IVRs) usando o teclado numérico do computador ou notebook com feedback visual em tempo real.
- ⏸️ **Retenção & Retomada Perfeita (Hold / Unhold)**: Controle nativo de chamadas com re-INVITE SIP e religação imediata das portas de áudio bidirecionais (microfone e alto-falante).
- 🔄 **Reconexão Manual com 1 Clique**: Botão de reconexão (`🔄`) na barra de status. Se a internet oscilar ou o registro cair, renova o SIP `REGISTER` instantaneamente no PBX.
- 🔒 **Instância Única Inteligente (Single Instance Lock)**: Impede a abertura de múltiplas instâncias acidentais; clicar no ícone restaura e foca na janela já aberta.
- 🤝 **Transferência Cega e Assistida Focada em Ramais**: Modais de transferência simplificados que listam diretamente os ramais da empresa com busca em tempo real por nome, número ou departamento.
- 👥 **Conferência de Áudio Multi-Participantes**: Conecte até 5 ramais ou números externos simultaneamente em uma mesma chamada.
- 🔔 **Campainha Secundária (Secondary Ringtone)**: Toque simultâneo no alto-falante do computador e no headset para nunca perder uma ligação.
- 🎨 **Interface Moderna & Compacta**: Design Dark Glassmorphism elegante, largura otimizada (340px) e botão de apagar (`⌫`) perfeitamente integrado.
- 🌐 **Multi-idioma Nativo**: Suporte completo em **Português (BR)**, **English** e **Español**.
- ⏱️ **48 Horas de Teste PRO Grátis**: Qualquer nova instalação recebe 2 dias de acesso irrestrito a todos os recursos da versão **PRO**.
- 🔄 **Atualizações Automáticas Integradas**: Atualize diretamente pelo app com verificação via GitHub Releases em 1 clique.
- 🛡️ **Zero Dependências Externas (Self-Contained)**: Runtime C++ (MSVCP140, VCRUNTIME140) embutido no instalador (Application-Local Deployment). Instala e funciona direto em qualquer máquina Windows sem necessidade de instalar pacotes adicionais.

---

## 📊 Comparativo de Edições (FREE vs. PRO)

| Recurso / Funcionalidade | Edição FREE 🎁 | Edição PRO ⭐️ |
| :--- | :---: | :---: |
| **Contas SIP Ativas** | 1 Conta | Multi-Contas Ilimitadas |
| **Transferência Cega (Blind Transfer)** | ✅ Sim | ✅ Sim |
| **Transferência Assistida com Consulta** | ❌ | ✅ Sim |
| **Conferência de Áudio (Até 5 Participantes)** | ❌ | ✅ Sim |
| **Gerenciador de Ramais por Departamentos** | ❌ | ✅ Sim (Vendas, Suporte, TI, etc.) |
| **Campainha Secundária (Headset + Alto-falante)** | ❌ | ✅ Sim |
| **Histórico Detalhado & Busca de Chamadas** | ✅ Sim | ✅ Sim |
| **Atendimento Automático & Mute / Hold** | ✅ Sim | ✅ Sim |
| **Reconexão Rápida SIP** | ✅ Sim | ✅ Sim |
| **Atualizações Automáticas de Software** | Manual | ✅ Sim (Automática em 1 clique) |

---

## 📥 Download e Instalação

Baixe as versões oficiais mais recentes do **Vortex SIP**:

### 💻 Windows (10 / 11 - 64 bits)
* 📦 **[Baixar Vortex SIP v2.9.0 (Instalador Setup)](https://github.com/JPHardtec/vortex-sip/releases/download/v2.9.0/Vortex-SIP-Pro-Setup-2.9.0.exe)** *(Recomendado — inclui atalhos e auto-update)*
* 🚀 **[Baixar Vortex SIP v2.9.0 (Versão Portátil / Portable)](https://github.com/JPHardtec/vortex-sip/releases/download/v2.9.0/Vortex-SIP-Pro-2.9.0.exe)** *(Execução direta sem necessidade de instalar)*

### 📱 Android
* 📲 **[Baixar Vortex SIP Mobile (APK v2.7.9)](https://github.com/JPHardtec/vortex-sip/releases/download/v2.7.9/Vortex-SIP-Mobile-v2.7.9.apk)**

---

## 📋 Histórico Recente de Versões (Changelog)

### v2.9.0 (Atual)
* **Suporte Completo ao Teclado Físico na URA**: Possibilidade de digitar números (0 a 9, *, #) diretamente no teclado do computador/notebook (linha superior e teclado numérico lateral / Numpad) durante chamadas ativas ou em menus de URA/IVR.
* **Feedback Visual Imediato no Teclado Virtual**: Os botões da discadora acendem com feedback de clique ao pressionar as teclas físicas equivalentes.
* **Proteção de Modais e Buscas**: Bloqueio de envio acidental de DTMF ao digitar nos campos de busca (Contatos, Ramais, Histórico) ou nos formulários de cadastro.
* **User-Agent SIP Dinâmico**: Identificação automática de versão na inicialização da pilha SIP.

### v2.8.11
* **Correção Crítica de Digitação/Foco de Teclado**: Substituição completa de caixas de diálogo nativas síncronas por modais assíncronos (`customConfirm`), eliminando o congelamento de foco nos campos de texto após exclusões.
* **Visualização de Setores Vazios**: Setores recém-criados permanecem visíveis imediatamente na interface mesmo antes de adicionar ramais.
* **Edição de Ramais e Contatos**: Adicionado botão de edição (lápis) para atualizar colaboradores, ramais e setores diretamente, sem necessidade de apagar e cadastrar novamente.
* **Integração Inteligente do Histórico**:
  - Botão `+` para cadastrar chamadas desconhecidas diretamente na agenda de contatos com número pré-preenchido.
  - Identificação visual automática de ramais internos da empresa com badge azul `Ramal` e botão de edição de ramal.
* **Contatos Simplificados**: Removido campo desnecessário de Departamento da agenda, mantendo foco ágil em Nome e Número.
* **Título Oficial Limpo**: Identificação do aplicativo padronizada como `Vortex SIP Desktop - PRO`.
* **Blindagem de Entrada**: Prevenção estrita de tipo na inicialização do modal de contatos, eliminando o erro de `[object PointerEvent]`.

### v2.8.5
* **Correção para Clientes ("Não foi possível encontrar o módulo especificado")**: Empacotamento das DLLs do Visual C++ Redistributable (MSVCP140, VCRUNTIME140) localmente na aplicação, eliminando falhas de inicialização em computadores sem o runtime C++ instalado.
* **Instância Única (Single Instance Lock)**: Evita múltiplas janelas do discador abertas ao mesmo tempo.
* **Botão de Reconexão Manual de Registro (`🔄`)**: Adicionado atalho rápido na barra de status para renovar o registro SIP imediatamente em caso de oscilação de rede.
* **Modais de Transferência Exclusivos para Ramais**: Foco direto em Ramais cadastrados nos fluxos de transferência cega e assistida, acelerando o atendimento.

### v2.8.4
* **Correção Nativa de Retomar Chamada (Hold / Unhold)**: Reescrita da retomada via re-INVITE no motor nativo PJSIP com preservação da contagem de áudio ativa (`aud_cnt=1`), garantindo o restabelecimento imediato do áudio bidirecional.
* **Ajustes de Layout**: Largura ajustada para 340px, garantindo visibilidade total do botão de apagar (`⌫`) e botões de teste de toque alinhados.

### v2.8.3
* **Estabilidade de Conferência e Logs**: Melhorias na troca de streams de conferência e logging em tempo real.

---

## 🔑 Como Ativar a Versão PRO

Para ativar a versão completa do **Vortex SIP PRO**:
1. Abra o **Vortex SIP**.
2. Clique no ícone de chave **🔑** no topo da barra de ferramentas.
3. Insira sua chave de licença no formato `VORTEX-PRO-XXXXXXXX-XXXXXXXX`.
4. Clique em **Ativar Licença**. Os recursos PRO são liberados instantaneamente!

---

## 🤝 Parceira e Distribuidora Autorizada

O **Vortex SIP** é homologado, implantado e distribuído pela **Soluciona Assessoria em T.I e Telecom**, empresa especializada em infraestrutura de redes, consultoria empresarial e soluções completas de PABX em Nuvem e Telefonia IP.

* 🌐 **Website**: [https://soluciona.inf.br](https://soluciona.inf.br)
* 💼 **Soluções Corporativas**: Telefonia IP, PABX Cloud, Troncos SIP, Consultoria e Suporte Especializado.

---

## 📄 Licença e Suporte

* **Desenvolvedor**: Jean Palumbo (JPHardtec)
* **Suporte Técnico**: Clientes atendidos pela Soluciona Assessoria em T.I e Telecom.
* **Direitos Autorais**: © 2024-2026 Jean Palumbo (JPHardtec). Todos os direitos reservados.
