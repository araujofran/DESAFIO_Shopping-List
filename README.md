# 📌 **README.md — Projeto DESAFIO_Shopping List**



---

# 🛒 **DESAFIO – Shopping List Automation (Automation Anywhere A360)**

Automação desenvolvida para completar o **Shopping List Challenge** da plataforma **Automation Anywhere** utilizando **RPA** para leitura de arquivo CSV e inserção automática dos itens no site.

---

## 📖 **Descrição do Projeto**

Este projeto tem como objetivo:

✔ Ler um arquivo **CSV** com os alimentos preferidos
✔ Separar as informações usando funções de string
✔ Inserir automaticamente cada item no campo "Shopping List"
✔ Adicionar cada alimento ao carrinho da página
✔ Confirmar os termos e submeter a ordem
✔ Finalizar o desafio com 100% de sucesso 🎯

A automação utiliza a dinâmica de **loops, parsing de texto e interação direta com elementos web**, consolidando habilidades essenciais do **Automation Anywhere A360**.

---

## 🧠 **Tecnologias utilizadas**

| Ferramenta                       | Função                                          |
| -------------------------------- | ----------------------------------------------- |
| **Automation Anywhere A360 Web** | Criação e execução do robô                      |
| **CSV/TXT Package**              | Leitura do arquivo `.csv` contendo os alimentos |
| **Browser Package**              | Automação de navegação web                      |
| **String Package**               | Separação de valores pela vírgula               |
| **Recorder Package**             | Interação com campo de texto e botões           |

---

## 🧩 **Fluxo do Sistema**


📍 **fluxo_sistema.png**


<img width="1498" height="678" alt="fluxo_sistema" src="https://github.com/user-attachments/assets/8589bb9a-a6d6-462e-a511-c0e8399a0794" />


---

### 🔁 Fluxo resumido

1️⃣ Abrir o navegador no site do desafio
2️⃣ Carregar o arquivo **shopping-list.csv**
3️⃣ Loop para cada linha do CSV
4️⃣ Dividir texto por vírgula → obter a fruta
5️⃣ Inserir o item no campo do site
6️⃣ Clicar no botão **Add Item**
7️⃣ Após o loop → selecionar **Yes**
8️⃣ Clicar em **Submit Order**
9️⃣ Exibir conquistas e finalizar

---

## 🔍 **Descrição das Ações do RPA**

| Nº | Ação                             | Função                                     |
| -- | -------------------------------- | ------------------------------------------ |
| 1  | CSV/TXT: Abrir                   | Carrega o arquivo com a lista de alimentos |
| 2  | Browser: Abrir                   | Acessa a página do desafio                 |
| 3  | Loop: Para cada linha            | Percorre item por item da lista            |
| 4  | String: Dividir                  | Separa o nome da fruta usando vírgula      |
| 5  | Capturar – Definir texto         | Insere a fruta no campo da página          |
| 6  | Capturar – Clicar "Add Item"     | Adiciona o alimento na lista               |
| 7  | Capturar – Selecionar “Yes”      | Confirma os termos                         |
| 8  | Capturar – Clicar “Submit Order” | Envia a compra com sucesso ✔               |

---

## 🏆 Conquista

Imagem comprovando a conquista de **100% accuracy + certificado**
👇 Salvar no repositório como:
📍 **conquista_vitoria.png**

---

## 👨‍💻 Autor

**Francisco Ferreira de Araujo**
Engenheiro de Inteligência Artificial • FIAP
📌 Agregando habilidades RPA através da plataforma **Automation Anywhere**
📎 LinkedIn: *(adicione quando quiser)*
📎 GitHub: *(link do repositório quando publicado)*

---

## 🚀 Motivação

Este é mais um passo na minha jornada de automação inteligente:
União entre **IA + RPA** para otimização de processos com precisão e alta performance.

---

## 📎 Estrutura recomendada do repositório

```
DESAFIO_Shopping List/
│
├── bot/
│   └── automacao_shopping_list.atmx   (se quiser adicionar o arquivo do bot)
│
├── images/
│   ├── fluxo_sistema.png
│   └── conquista_vitoria.png
│
├── shopping-list.csv  (opcional - sem dados pessoais)
│
└── README.md
```




