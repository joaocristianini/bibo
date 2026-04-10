# 📖 Projeto: O Decifrador (Cifra de César)

Este repositório contém o desenvolvimento de um sistema de descriptografia baseado no algoritmo da Cifra de César. O projeto aplica rigorosamente práticas de engenharia de software alinhadas aos modelos de maturidade **CMMI Nível 2** e **MPS-BR Nível G**.

---

## 👥 Integrantes e Papéis (Matriz RACI)
| Atividade | Responsável | Papel |
| :--- | :--- | :--- |
| **Liderança** | Matheus Gago | Líder de Projeto |
| **Desenvolvimento** | João Matheus / Matheus | Developers (Dev) |
| **Qualidade** | Guilherme Tavares | Quality Assurance (QA) |
| **Gerência de Configuração** | João Pedro | Configuration Manager (CM) |

---

## 🎯 1. Objetivo
O foco é a execução de um processo estruturado de desenvolvimento, garantindo:
Correta descriptografia de mensagens.
Organização, padronização e modularização do código.
Simulação de ambiente profissional seguindo normas de qualidade.

---

## 📌 2. Escopo do Projeto

### ✅ Funcionalidades Incluídas
Descriptografia utilizando a Cifra de César via terminal.
Tratamento de maiúsculas/minúsculas e preservação de caracteres especiais/espaços.
Gestão via **Kanban** e controle de versão com **Git**.
Processo de **Peer Review** (revisão de código).

### ❌ Não Incluído
Criptografia de mensagens e quebra por força bruta.
Interface gráfica avançada (GUI) ou banco de dados.
Uso de IA ou processamento em nuvem.

---

## ⚙️ 3. Requisitos (Principais)
| ID | Tipo | Descrição |
| :--- | :--- | :--- |
| **RF01** | Funcional | Receber mensagem e chave de deslocamento. |
| **RF03** | Funcional | Descriptografar mantendo a integridade dos caracteres. |
| **RF07** | Funcional | Validar entradas inválidas (ex: letras na chave). |
| **RNF01** | Não Funcional | Tempo de resposta máximo de 2 segundos. |
| **RNF06** | Não Funcional | Revisão de código obrigatória antes do merge. |

---

## 🔄 4. Processo de Desenvolvimento
1.  **Planejamento:** Definição de escopo e tarefas no Kanban.
2.  **Implementação:** Codificação modular com comentários explicativos.
3.  **Qualidade (QA):** Testes de casos extremos e revisão de código.
4.  **Gerência de Configuração:** Commits organizados e controle de versão.

---

## ⏱️ 5. Cronograma e Estimativas
### Datas Marco:
**Fim da Arquitetura:** 10/04
**Fim da Codificação:** 15/04
**Fim da Revisão de Qualidade:** 17/04

### Esforço Estimado (Horas):
| Atividade | Horas Estimadas |
| :--- | :--- |
| Planejamento | 4h |
| Codificação | 7h |
| Testes | 8h |
| Correções / Revisão | 10h |

---

## ⚠️ 6. Gerência de Riscos
| Risco | Mitigação |
| :--- | :--- |
| **Falha no Git** | Backup e commits frequentes. |
| **Erro no algoritmo** | Testes intensivos e Peer Review. |
| **Atraso no Cronograma** | Priorização do essencial (MVP). |

---

## 🧪 7. Enigma de Teste (Validação)
Para validar o sistema, utilize o seguinte caso de teste:
**Entrada:** Krod, pxqgr!
**Chave:** 3
**Saída Esperada:** Olá, mundo!
**Explicação:** O sistema desloca 3 posições para trás no alfabeto.

---

## 🧠 8. Conclusão
O projeto "O Decifrador" demonstra a aplicação prática de conceitos de engenharia de software, provando que processos organizados contribuem diretamente para um software confiável, auditável e de fácil manutenção.

## 🖼️ Imagem Fluxograma

<img width="304" height="1024" alt="image" src="https://github.com/user-attachments/assets/59e11676-9aeb-4a0f-ba32-15aa3f35e466" />
