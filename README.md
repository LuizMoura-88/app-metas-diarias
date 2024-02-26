
## 🖥️ Gerenciador de Hábitos

Está aplicação foi idealizada pela escola de tecnologia [codante.io](https://codante.io/), a proposta desta aplicação é oferecer um serviço de gerenciador de hábitos baseando-se em mobile-first, cada hábito cadastro apresenta na tela inicial os últimos 7 dias oferecendo uma análise de como está sendo executado um hábito uma vez implementado. Ao clicar em um hábito especifico, a aplicação oferece a possibilidade de efetuar um checklist de tarefas concluídas ou não em um período mensal. Os dados são persistidos no KV (Key-Value) da plataforma de desenvolvimento Vercel denominado Redis, a posposta do backend desenvolvido para esta aplicação é ter uma arquitetura simples porem bem implementada agregando as funcionalidades que o Next.js e a Vercel oferecem, tornando o código simples e legível. Implementar esse projeto desenvolveu minhas habilidades técnicas (HardKills)   ao manusear as ferramentas Next.js,TypeScript e Tailwind.

Recursos oferecidos:

- Cadastrar hábitos.
- Excluir hábitos.
- Gerenciar tarefas realizadas ou não (ChekList).

##

### 📌 Layout do Projeto 
<img width="2152" alt="processo_2" src="https://github.com/LuizMoura-88/app-metas-diarias/assets/122941117/118c9e98-8e0b-428e-83e6-36d634888b0c">

##

### 📌 Tecnologias Utilizadas      
```
  "dependencies": {
    "@types/node": "20.4.2",
    "@types/react": "18.2.15",
    "@types/react-dom": "18.2.7",
    "@vercel/kv": "^0.2.4",
    "autoprefixer": "10.4.14",
    "eslint": "8.45.0",
    "eslint-config-next": "13.4.10",
    "next": "13.4.10",
    "postcss": "8.4.26",
    "react": "18.2.0",
    "react-dom": "18.2.0",
    "tailwindcss": "3.3.3",
    "typescript": "5.1.6",
    "vercel": "^33.5.1"
  }
```
##

### Como rodar o projeto ✅
* ##### Faça o download do repositório, copie para uma pasta local, abra esta pasta por uma IDE (Ambiente de Desenvolvimento Integrado) foi utilizado o VSCODE
```
1° Copiar link: git@github.com:LuizMoura-88/app-metas-diarias.git
2° Abrir a linha de comando de seu computador local, escolher um diretório e efetuar o git clone:  git clone git@github.com:LuizMoura-88/app-metas-diarias.git
3° Após efetuar o download do repositório remoto abrir o arquivo em sua IDE (ambiente de desenvolvimento integrado).
4° Em sua linha de comando efetuar o comando npm run dev
5° Escolha e aperte `ctrl+click` o link que será gerado automaticamente pelo sistema exemplo: url: http://localhost:3000
```
##

### Como utilizar o serviço ✅
<details>
  <summary>Acessar video</summary>
  https://github.com/LuizMoura-88/web-site-receitas/assets/122941117/8432dbe2-bb27-46cc-b48b-25e09b101515
</details>

##

🌐 [Visitar - WebSite](https://app-metas-diarias.vercel.app/novo-habito)


##

## 📌 Informações Adicionais
* A prentensão foi integrar aplimentar uma aplicação que utilizando next.js e typescript.
* iniciativa do projeto tem como origem o seguinte endereço: [🌐](https://codante.io/mini-projetos/gerenciador-de-habitos-com-nextjs)

##

## ⚠️ Problemas enfrentados
* Encontrei dificuldade em realizar a integração entre next.js e kv/vercel por ser uma tecnologia recente para mim.
  
##
  
## ⏭️ Próximos passos

* Implementar testes unitários.
* refatoração de código, baseando-se nos princípios de clean code.
* implementar novas funcionalidades.

##

### ✅  Autor
Luiz Guilherme da Silva Moura <br/>
[LinkedIn](https://www.linkedin.com/in/luiz-moura-b60099252/)
