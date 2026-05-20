# 🔌 Connect — Navegação Inteligente de Camadas para QGIS

> Alterne entre grupos de camadas com um atalho do teclado, sem perder o foco no que importa.

---

## 📖 Sobre o Plugin

O **Connect** é uma ferramenta de produtividade para usuários do QGIS que trabalham com projetos densos e árvores de camadas complexas. Em vez de marcar e desmarcar grupos manualmente, o Connect oferece uma navegação fluida e centralizada: você escolhe o grupo, ele cuida da visibilidade.

---

## ✨ Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| 🗂️ **Gestão por Contexto** | Adicione qualquer grupo da legenda ao painel com um clique direito |
| ⌨️ **Navegação por Teclado** | Use `↑` e `↓` para alternar entre grupos — ideal para comparações rápidas |
| ▶️ **Controle Sequencial** | Botões **Anterior** e **Próxima** para um fluxo de trabalho ordenado |
| ⚡ **Atalho Rápido** | Pressione `F9` para exibir ou ocultar o painel instantaneamente |
| 🖱️ **Drag-and-Drop** | Reordene os grupos no painel arrastando e soltando |
| 💾 **Memória do Projeto** | A lista de grupos é salva no próprio arquivo `.qgs`/`.qgz` — sem reconfiguração ao reabrir |

---

## 🚀 Como Usar

1. Na **árvore de camadas (Legenda)**, localize o grupo desejado.
2. Clique com o **botão direito** sobre o grupo e selecione **"Connect: Adicionar grupo"**.
3. Abra o **painel do Connect** — ou pressione `F9` se estiver fechado.
4. Navegue entre os itens da lista. O QGIS gerencia a visibilidade automaticamente.

---

## ⚙️ Requisitos

- **QGIS:** 3.22 (Białowieża) ou superior
- **Linguagem:** Python 3 com interface PyQt5

---

## 📦 Instalação

### Via QGIS Plugin Manager *(recomendado)*
1. Abra o QGIS.
2. Vá em **Complementos → Gerenciar e Instalar complementos -> Instalar a partir do ZIP**.
3. Pesquise por **Connect**.

---

## 🗺️ Casos de Uso

- **Comparação de cenários:** alternar rapidamente entre camadas de planejamento urbano, uso do solo ou cobertura vegetal.
- **Análise temporal:** navegar entre grupos representando diferentes anos ou períodos.
- **Apresentações e revisões:** exibir contextos específicos do mapa sem distrações.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

- Abrir uma [issue](../../issues) para reportar bugs ou sugerir melhorias.
- Enviar um *pull request* com correções ou novas funcionalidades.

---

## 👩‍💻 Autora

Desenvolvido por **Ana Carolina Santos de Andrade**  
Foco em otimização de fluxos de trabalho geoespaciais.

---

## 📄 Licença

<!-- Adicione aqui a licença do seu projeto, ex: MIT, GPL-2.0 -->
Este projeto está sob a licença [MIT](LICENSE).
