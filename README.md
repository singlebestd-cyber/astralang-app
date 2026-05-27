# 🚀 AstraLang AlphaCompiler v12.5 & Jarvis 3D IDE Standalone

AstraLang AlphaCompiler é um ecossistema portátil de compilação autoregressiva multi-alvo com análise preditiva de hardware em tempo real e proteção estrita de memória. O projeto resolve o problema clássico de opacidade em pipelines de otimização de código, oferecendo um cockpit holográfico tridimensional que expõe o Control Flow Graph (CFG) e interage nativamente via barramento IPC/Sockets de baixa latência.

---

## ⚙️ Arquitetura de Sistemas & Engenharia de Redes

O ecossistema adota uma topologia descentralizada dividida em duas camadas principais, quebrando as barreiras de isolamento entre ambientes virtualizados Linux (WSL2) e o sistema hospedeiro (Windows Developer Environment):

*   **IA & Backend Core (WSL2 / Linux Kernel)**: Motor construído em Python alimentado por uma Rede Neural Multi-Variável profunda em **PyTorch 2.0**. Ele intercepta as transformações semânticas da árvore AST, calcula métricas de *cache miss* e estresse térmico, e gerencia um banco de dados analítico estruturado em arquivos `.jsonl` e `.astra` protegido por **Mutex Locks (Thread-Safe)** contra condições de corrida.
*   **Jarvis 3D UI Renderer (Windows Localhost)**: Interface standalone em tela cheia construída em HTML5 e WebGL nativo rodando a **60 FPS estáveis**. A comunicação é realizada de forma reativa através de requisições assíncronas AJAX/Fetch cruzando as pontas de rede. 

> 🛡️ **Bypass de Segurança CORS**: O servidor possui uma camada customizada de cabeçalhos HTTP que anula os bloqueios de política de mesma origem (*Same-Origin Policy*) do Google Chrome, garantindo a integridade dos pacotes de telemetria sem expor vulnerabilidades de cross-bridge.

---

## 🛡️ Recursos Incorporados de Cibersegurança

*   **Análise Estática Nativa (SAST)**: Scanner semântico acionado antes de qualquer mutação de pipeline, bloqueando execuções espúrias e mitigando ameaças de *Integer Overflow* nas fronteiras físicas de registradores de 32 bits ($i32$).
*   **Isolamento de Memória RAII**: Gerenciamento automático de recursos em tempo de execução para prevenir vazamento de descritores de sockets e exaustão de armazenamento de dados em disco.

---

## 📊 Telemetrias Monitoradas em Tempo Real

À medida que os nós neon da árvore de passes são manipulados ou reordenados dinamicamente via arrasto no Canvas, o oráculo neural prevê instantaneamente:
1.  **Aceleração de Speedup**: Previsão matemática de ganho de performance baseada nos passes LLVM aplicados.
2.  **Taxa de Cache Miss L1/L2**: Desempenho estimado da hierarquia de memória do silício.
3.  **Risco de Gargalo Térmico**: Índice estresse calórico da CPU, disparando gatilhos automáticos para chaveamento CUDA paralelo em GPU (`@target backend_gpu`).

---

## 🕹️ Como Executar o Ecossistema

Este componente foi compilado com oPyInstaller em um formato **One-File autônomo**, contendo todas as dependências (incluindo runtimes C++ e drivers portáteis) embutidas com **zero instalações prévias necessárias**.

### 💻 No Linux / WSL2:
1. Conceda permissão de execução ao binário extraído do pacote de distribuição:
   ```bash
   chmod +x dist/app
   ```
2. Inicialize o barramento de rede e o cockpit Jarvis rodando o script automatizado:
   ```bash
   ./run_jarvis.sh
   ```

---

## 📄 Licença e Propriedade Intelectual
Este componente público é disponibilizado sob a **Licença MIT**, oferecendo isenção estrita de responsabilidade e garantia jurídica de portabilidade de mercado aberta para uso corporativo, acadêmico ou comercial.

**Desenvolvido com foco em alta performance e cibersegurança por  (Junior Cyber Security Engineer) © 2026.**
