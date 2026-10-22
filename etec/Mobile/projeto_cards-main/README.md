# 🃏 Projeto Cards App (Android Studio)

Uma aplicação Android nativa desenvolvida em **Kotlin** para exibição e gerenciamento de cards interativos, aplicando conceitos de interface de usuário (UI/UX) e boas práticas de desenvolvimento mobile.

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como parte de uma atividade prática. O objetivo principal é demonstrar o uso de componentes visuais modernos do Android (como `RecyclerView`, `CardView` e layouts responsivos) integrados com a linguagem **Kotlin** e a ferramenta de build **Gradle**.

---

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Kotlin
* **IDE:** Android Studio
* **Build System:** Gradle (Kotlin DSL - `.kts`)
* **SDK Mínimo:** API 24 (Android 7.0)
* **SDK Target:** API 36

---

## 📁 Estrutura do Projeto

```text
projeto_cards-main/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/.../     # Código fonte (Activities, Adapters, Models)
│   │   │   └── res/               # Recursos (Layouts XML, Drawables, Values)
│   └── build.gradle.kts           # Configurações do módulo do aplicativo
├── gradle/                        # Wrappers e configurações do Gradle
├── build.gradle.kts               # Configurações do projeto raiz
└── settings.gradle.kts            # Módulos e repositórios do projeto
