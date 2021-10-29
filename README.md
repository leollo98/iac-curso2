# Resumo do projeto

Segundo projeto de Infraestrutura como código, utilizando Terraform para provisionamento, Ansible para as configurações e dependências, e AWS como provedor da infraestrutura.

## 🔨 Funcionalidades do projeto

A partir desse projeto você pode:

- Criar maquinas virtuais na EC2
- Separar o seu codigo em 2 ambientes, um de produção e um de desenvolvimento
- configurar as maquinas para executar uma API em Django automaticamente

## ✔️ Técnicas e tecnologias utilizadas

Neste App são exploradas as seguintes técnicas e tecnologias:

- **Criação de maquinas na EC2**: criação de maquinas virtuias no ambiente EC2 (Elastic Compute Cloud) da AWS
- **configuração das maquinas**: configura as maquians de forma automatica ultilizando o Ansible
- **criação de playbooks**: os playbooks são parte integral do ansible e descrevem quais os passos a serem seguidos
- **separação de ambientes**: 2 ambientes separados, construidos de forma automatica pelo Terraform, reultilizando codigo.
- **Execução de APIs**: como iniciar um API automaticamente apos a configuração da maquina

## 📁 Acesso ao projeto

Você pode [baixar o zip](https://github.com/leollo98/iac-curso2/archive/refs/heads/Aula_5.zip) ou [acessar o código fonte](https://github.com/leollo98/iac-curso2/tree/Aula_5) do projeto final:

## 🛠️ Abrir e rodar o projeto

O projeto foi desenvolvido no VSC (Visual Studio Code), sendo assim, instale o VSC (pode ser uma versão mais recente) e, na tela inicial, procure a opção extenções, ou aperte Ctrl+Shift+X, e busque por HashiCorp Terraform, assim teremos o suporte do intellisense, tornando o trabalho de escrever o código mais rapido.

> Caso baixou o zip, extraia o projeto antes de procurá-lo, pois não é possível abrir via arquivo zip

Vá até a paste a abra a pasta do projeto. Apos abrir o projeto abra um terminal, pode ser o integrado com o VSC, navegue até as pastas `infra/`,`env/Prod` e `env/DEV` e execute o comando `terraform init` dentro delas, agora temos o terraform iniciado e podemos começar a ultiliza-lo. Para criar a infraestrutura, execute o terraform apply em uma das pastas de Produção (`env/Prod`) ou de Desenvolvimento (`env/DEV`) de acordo com o ambiente desejado.🏆

## 📚 Mais informações do curso

<!--Gostou do projeto e quer conhecer mais? Você pode [acessar o curso que desenvolve o projeto desde o começo](https://www.alura.com.br/curso-online-kotlin-orientacao-objetos)!-->

<!--Esse curso faz parte da [formação de Kotlin da Alura](https://www.alura.com.br/formacao-kotlin)-->
