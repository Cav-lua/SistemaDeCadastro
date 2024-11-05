# **Sistema de Cadastro de Usuários**

> Um aplicativo Android para cadastrar e visualizar informações de usuários.

## 📱 Descrição

O **Sistema de Cadastro de Usuários** permite ao usuário registrar informações como nome, telefone e endereço.
Os dados são armazenados em uma lista e podem ser visualizados em uma interface simples e intuitiva.

## 🔧 Funcionalidades

- [x] Tela principal com opções de cadastro e visualização de usuários
- [x] Cadastro de usuários com nome, telefone e endereço
- [x] Exibição dos usuários cadastrados em uma lista
- [x] Mensagens de confirmação e aviso

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **EditText**, **Button** e **TextView** para entrada e exibição de dados

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone https://github.com/Cav-lua/sistema-cadastro-usuarios.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/br/com/senacrs/sistemadecadastro
│   │   │   │   ├── MainActivity.java        # Atividade principal com a lógica do sistema
│   │   │   │   ├── Registro.java            # Classe modelo para armazenar dados do usuário
│   │   │   │   ├── TelaPrincipal.java       # Tela principal do aplicativo
│   │   │   │   ├── TelaCadastroUsuario.java # Tela de cadastro de usuários
│   │   │   │   └── TelaListagemUsuarios.java# Tela de listagem de usuários cadastrados
│   │   │   ├── res
│   │   │   │   ├── layout
│   │   │   │   │   ├── activity_main.xml     # Layout da tela principal
│   │   │   │   │   ├── cadastro_de_usuarios.xml # Layout da tela de cadastro
│   │   │   │   │   └── listagem_usuarios_cadastrados.xml # Layout da tela de listagem
│   │   │   │   └── values
│   │   │   │       ├── strings.xml           # Strings usadas no app
│   │   │   │       └── colors.xml            # Cores definidas no projeto
│   └── build.gradle                            # Configuração do Gradle
└── README.md                                   # Este arquivo
```
🎨 Design e Prototipagem
A interface do app foi criada usando ConstraintLayout para garantir responsividade em diferentes tamanhos de tela.
O design é focado na usabilidade, proporcionando uma experiência intuitiva ao usuário.

🖥️ Telas do Aplicativo
Tela Principal

![Captura de tela 2024-11-05 020034](https://github.com/user-attachments/assets/4f99a44d-5790-48f1-926e-ebeee7a05bf0)

Listagem

![Captura de tela 2024-11-05 020103](https://github.com/user-attachments/assets/0c3bb3f7-6168-46bd-85d1-07cf07a90f05)

👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob a MIT License.
