# Codeceptjs - Automação de Testes Web

  

- 📌 Este projeto faz parte do aprendizado na Formação Agile Test Engineer na escola [E2ETreinamentos](https://e2etreinamentos.com.br/), o objetivo foi ensinar aos alunos contruir uma base de framework para automação de testes web em Codeceptjs.

- 💻 Para os testes realizados usei o site [http://teststore.automationtesting.co.uk/](http://teststore.automationtesting.co.uk/) , que é um e-commerce fictício.

  
  

## 👨🏻‍💻Tecnologias Utilizadas

- [Codeceptjs](https://codecept.io/quickstart/) - Framework de testes automatizados

- [Playwright](https://codecept.io/helpers/Playwright/#playwright) - Helper usado no projeto

- [Node.js](https://nodejs.org/en/) - Plataforma de desenvolvimento

- [Mochawesome](https://codecept.io/reports/#html) - Reports de execução de testes em HTML

  

#### 🎨 Padrão de design do projeto:

-  **Modelo de objeto de página** (por meio **Page Object** )

  
  

## 🧪 Suítes de Teste:

Os testes funcionais foram distribuidos nas seguintes suítes:

  

|Login                                    Teste                   |
|----------------|-------------------------------|-----------------|

|CT01- deve realizar login com sucesso                  |`'Positivo'` |

|CT02- não deve realizar login com email inválido |`'Negativo'` |

|CT03- não deve realizar login com sena inválida |`'Negativo'` |

  

## 🚀 Como executar o projeto

Essas instruções permitiração que você obtenha uma cópia do projeto sua máquina local para fins de teste.
  

####  Clonar o projeto:

```

git clone <complemento url para clone>

```


#### Execute o comando abaixo:

```
git remote add origin <complemento url do projeto>
```

  

### 🤖 Execute o comando abaixo para instalar das dependências do projeto:

```
npm install

npm install --save-dev playwright

npm i codeceptjs --save-dev

npm i mochawesome mocha -D
```

### ⚙️Execute o comando abaixo para rodar os testes via linha de comando:
 

Execute o comando abaixo para rodar os testes:

```
npx codeceptjs run
```

Execute o comando abaixo para rodar os testes por tags:

```
npx codeceptjs run --grep "nomeDaTag"
```

Execute o comando para rodar os testes e obter relatórios:

```
codeceptjs run --reporter mochawesome
```

  

## 📌 Notas Gerais



Projeto em desenvolvimento!

Feito com ❤️ por [E2E Treinamentos](https://github.com/repoe2e) 😊

⌨️ Me contate pelo [LinkedIn](https://www.linkedin.com/company/e2e-treinamentos/) 😊

