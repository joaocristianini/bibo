# 📄 PROJETO – O DECIFRADOR (CIFRA DE CÉSAR)

Este repositório contém o desenvolvimento de um sistema de descriptografia baseado no algoritmo da Cifra de César. O projeto aplica rigorosamente práticas de engenharia de software alinhadas aos modelos de maturidade **CMMI Nível 2** e **MPS-BR Nível G**.


## 👥 Integrantes e Papéis (Matriz RACI)
| Atividade | Responsável | Papel |
| :--- | :--- | :--- |
| **Liderança** | Matheus Gago | Líder de Projeto |
| **Desenvolvimento** | João Matheus / Matheus | Developers (Dev) |
| **Qualidade** | Guilherme Tavares | Quality Assurance (QA) |
| **Gerência de Configuração** | João Pedro | Configuration Manager (CM) |


---

## 🎯 1. Objetivo
Desenvolver um sistema de descriptografia capaz de identificar e decodificar mensagens utilizando o algoritmo da Cifra de César, aplicando boas práticas de engenharia de software alinhadas aos modelos CMMI Nível 2 e MPS-BR Nível G.

O projeto tem como foco não apenas a implementação do algoritmo, mas também a execução de um processo estruturado de desenvolvimento, incluindo planejamento, controle de qualidade, versionamento e validação do produto.

**O sistema deve garantir:**
Correta descriptografia de mensagens
Organização e padronização do código
Aplicação de práticas de qualidade
Simulação de um ambiente profissional de desenvolvimento

---

## 📌 2. Escopo

### ✔️ Funcionalidades Incluídas
O sistema permitirá:
Entrada de mensagens criptografadas
Entrada da chave de deslocamento
Processamento da descriptografia
Exibição do resultado em texto claro

**✅ Inclui:**
Descriptografia utilizando a Cifra de César
Entrada via terminal
Tratamento de letras maiúsculas e minúsculas
Preservação de caracteres especiais
Validação básica de entrada
Código modular
Testes manuais
Uso de Git
Revisão de código (peer review)
Uso de Kanban
Documentação do projeto

**❌ Não Inclui:**
Outros algoritmos (Base64, RSA, AES etc.)
Criptografia
Quebra automática da cifra
Interface gráfica avançada
Banco de dados
APIs externas
Execução em nuvem
Inteligência artificial
Testes automatizados avançados

---

## ⚙️ 3. Requisitos Funcionais
**RF01:** Receber mensagem criptografada
**RF02:** Receber chave de deslocamento
**RF03:** Descriptografar corretamente
**RF04:** Preservar caracteres especiais
**RF05:** Manter maiúsculas e minúsculas
**RF06:** Exibir resultado corretamente
**RF07:** Validar entradas inválidas

---

## ⚙️ 4. Requisitos Não Funcionais
**RNF01:** Tempo de resposta até 2 segundos
**RNF02:** Código legível e documentado
**RNF03:** Uso de Git
**RNF04:** Padronização de código
**RNF05:** Facilidade de manutenção
**RNF06:** Revisão de código obrigatória
**RNF07:** Baixo acoplamento e alta coesão

---

## 🔄 5. Processo de Desenvolvimento

**Planejamento:** Definição do escopo, Organização no Kanban e Definição de papéis.
**Implementação:** Desenvolvimento da lógica, Código modular e Comentários explicativos.
**Qualidade (QA):** Testes funcionais, Testes de casos extremos e Revisão de código.
**Correções:** Ajustes após testes e Refatoração.
**Gerência de Configuração:** Uso de Git, Commits organizados e Controle de versões.
**Testes Finais:** Validação completa.

---

## ⏱️ 6. Cronograma
**Fim da arquitetura:** 10/04
**Fim da codificação:** 15/04
**Fim da revisão de qualidade:** 17/04

---

## 🗺️ 7. Planejamento (Mapa – CMMI/MPS-BR)

### 📊 Estimativas
| Atividade | Tempo |
| :--- | :--- |
| Planejamento | 4h |
| Configuração | 2h |
| Codificação | 7h |
| Testes | 8h |
| Correções | 6h |
| Revisão | 4h |

### 👥 Papéis (RACI)
| Atividade | Responsável | Papel |
| :--- | :--- | :--- |
| **Líder** | Matheus | Liderança |
| **Dev** | João Matheus / Matheus | Desenvolvimento |
| **QA** | Guilherme | Qualidade |
| **CM (Git)** | João Pedro | Gerência de Configuração |

### ⚠️ Riscos
| Risco | Mitigação |
| :--- | :--- |
| Falha no Git | Backup e commits frequentes |
| Erro no algoritmo | Testes e revisão |
| Falta de integrante | Redistribuição de tarefas |
| Atraso | Priorização do essencial |

---

## 🧪 8. Enigma de Teste
**Entrada:** Krod, pxqgr!
**Chave:** 3
**Saída esperada:** Olá, mundo!
**Explicação:** Deslocamento de 3 posições para trás no alfabeto.

**Outros exemplos:**
Khoor → Hello
Dwwdfn → Attack

---

## 🧠 9. Conclusão
O projeto “O Decifrador” possibilitou a aplicação prática de conceitos de engenharia de software, alinhados aos modelos CMMI e MPS-BR. Além da implementação da Cifra de César, a equipe seguiu um processo estruturado, envolvendo planejamento, controle de versão, revisão de código e testes, garantindo a qualidade do sistema. Conclui-se que a utilização de boas práticas e processos organizados contribui diretamente para o desenvolvimento de um software mais confiável, organizado e de fácil manutenção.

## 🖼️ Imagem Fluxograma

<img width="304" height="1024" alt="image" src="https://github.com/user-attachments/assets/59e11676-9aeb-4a0f-ba32-15aa3f35e466" />
