# 🚀 AlphaCompiler v12.5 & Jarvis 3D IDE Standalone

Esta release disponibiliza o pacote binário executável unificado de produção da **AstraLang**, contendo a esteira completa do compilador autoregressivo integrado com análise estática de cibersegurança e inferência de redes neurais multi-alvo [🚀1, 🚀4].

## 🛡️ Recursos Incorporados de Engenharia

*   **Core Execution Engine (v4.0):** Orquestrador standalone thread-safe protegido por **Mutex Lock** contra condições de corrida e colisões assíncronas de escrita em disco [🚀1].
*   **Aritmética de Custo Zero (Pilar 7):** Expansão in-place de blocos funcionais e otimizações automáticas de registradores SSA através do LLVM Intermediate Representation stream [🚀4].
*   **Cibersegurança SAST (v1.7):** Scanner estático nativo acionado antes da compilação, bloqueando e abortando a esteira caso detecte violações de **Integer Overflow (i32 boundary)** ou injeções espúrias em ponteiros opacos ($ptr$) [🚀1, 🚀4].
*   **Oráculo Multi-Variável Autónomo:** Rede Neural profunda construída em **PyTorch 2.0** que analisa o Control Flow Graph (CFG) e prevê simultaneamente: aceleração de speedup, taxa de cache miss L1/L2 e risco de gargalo térmico da CPU, sugerindo o chaveamento automático para GPU quando necessário [🚀1, 🚀4].
*   **Cockpit Standalone 3D (UX Jarvis):** Interface tridimensional responsiva gerada em WebGL rodando a 60 FPS fluídos com telemetrias e barras dinâmicas reativas atualizadas via barramento HTTP IPC direto de redes [🚀1].

---

## 🕹️ Como Executar no Seu Sistema Operacional

Este binário foi compilado no formato **One-File autônomo**, contendo todas as dependências de infraestrutura (incluindo runtimes C++ e drivers CUDA) embutidos de forma portátil, exigindo **zero instalações prévias** [🚀1].

### 💻 No Linux / WSL2:
1. Descarregue o arquivo compactado `.zip` e extraia o binário `app` no seu diretório.
2. Abra o terminal na pasta e conceda a permissão de execução do sistema:
   ```bash
   chmod +x app
   ```
3. Dispare o cockpit holográfico na hora executando:
   ```bash
   ./app
   ```

---

## 📄 Licença de Distribuição
Este componente público é disponibilizado sob a **Licença MIT**, oferecendo isenção estrita de responsabilidade e garantia jurídica de portabilidade de mercado aberta para uso corporativo ou acadêmico.

**Desenvolvido com orgulho por Gabriel (Junior Cyber Security Engineer) © 2026.**
