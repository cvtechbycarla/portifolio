# 🖨️ Controle de Impressora Térmica Elgin (i8 / i9) em C
### (Coloque aqui o nome do seu projeto)
---

## 📘 Sobre o Projeto

Este projeto foi desenvolvido por alunos com o objetivo de criar uma aplicação em *C* capaz de se comunicar com a impressora térmica *Elgin i8 ou i9, utilizando a biblioteca *E1_Impressora01.dll**, login, menu interativo e comandos de impressão, gaveta e sinal sonoro.  
O trabalho faz parte da disciplina de *Programação em C*.

---

## 🧰 Tecnologias Utilizadas

- *Linguagem C (main.c)*
- *Compilador GCC / Code::Blocks*
- *Biblioteca E1_Impressora01.dll (32 bits x86 ou 64 bits x64)*
- *Arquivos XML (XMLSAT.xml e CANC_SAT.xml)*

---

## 📁 Estrutura do Projeto

main.c → Código-fonte principal do programa em C
E1_Impressora01.dll → Biblioteca da Elgin (x86 ou x64, na raiz do projeto)
XMLSAT.xml → XML de teste para impressão de cupom SAT (na raiz)
CANC_SAT.xml → XML de teste para cancelamento SAT (na raiz)


---

## ⚙️ Instalação e Execução

### 🔽 1. Baixar o Projeto do GitHub
1. Acesse o repositório.
2. Clique no botão *Code*.
3. Selecione *Download ZIP*.
4. Aguarde o download.

### 📦 2. Extrair o Arquivo ZIP
1. Vá até o local onde o arquivo foi salvo.
2. Clique com o botão direito → *Extrair aqui* / *Extract All*.
3. Será criada uma nova pasta com os arquivos.

### 🧭 3. Compilar e Executar (32 bits x86 ou 64 bits x64)
1. Confira os bits do compilador com gcc -dumpmachine (x86_64-w64-mingw32 = *64 bits, use a DLL x64; mingw32 ou i686-w64-mingw32 = **32 bits*, use a DLL x86).
2. Coloque a E1_Impressora01.dll correspondente, XMLSAT.xml e CANC_SAT.xml na pasta/raiz do projeto.
3. Ligue a impressora e conecte o cabo USB.
4. No terminal, dentro da pasta do projeto, execute:
   - gcc main.c -o impressora.exe
   - impressora.exe
5. Faça o login de teste (*usuário:* admin, *senha:* 1234, até 3 tentativas) e use o menu.

---

## 🧪 Testes

- Login com até 3 tentativas (admin / 1234)
- Opções 1 a 3: Configurar, abrir e fechar conexão
- Opções 4 a 6: Imprimir texto, QR Code e código de barras
- Opções 7 e 8: Imprimir XML SAT e cancelamento SAT
- Opções 9 a 11: Abrir gaveta (Elgin), abrir gaveta e sinal sonoro
- Opção 0: Sair

---

## 📚 Documentação Adicional

- Manual da Impressora *Elgin i8 / i9*
- Documentação *Elgin Developer Community*: https://elgindevelopercommunity.github.io/group___m1.html

---

## 👥 Autores  
(em ordem alfabética)

- Carla Adriana Vieira
- Guilherme Martins de Almeida
- João Victor Ferreira Teles
- Wallace Pereira Bessa