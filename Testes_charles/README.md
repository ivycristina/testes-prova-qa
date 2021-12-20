# Automações de Testes Web - Site Americanas

Esse projeto implementa todos os fluxos de testes automatizados do Teste de Web para vaga QA

> Utilizando a stack: Ruby + Cucumber + capybara, esse projeto tem o intuito de implementar os testes para compra de um produto em web. 

- [Ruby](https://www.ruby-lang.org/pt/)
- [cucumber](https://cucumber.io/)
- [capybara](- [capybara]

## Arquitetura do projeto

Toda descrição e explicação sobre a arquitetura do projeto pode ser vista [aqui](https://drive.google.com/file/d/1JnrR4z01-a3m4alm7hE7L8k_z_Q3N7oa/view?usp=sharing). 


## Execução

Para executar os testes, faça toda a configuração do seu ambiente, e faça o clone do projeto em sua máquina.

* para instalar as dependencias, acesse o diretório do projeto pelo seu console, e execute o comado:

```sh
bundle install
```
* após concluir a instalação, para executar o teste, execute o comando abaixo, substituindo "@tag" para a tag do teste que você deseja executar.

```sh
cucumber -t @suatag
```