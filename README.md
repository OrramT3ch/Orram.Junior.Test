Orram Gestão: Teste prático para Frontend Javascript Developer

Este é o teste usado por nós aqui da Orram Gestão para avaliar tecnicamente os candidatos a nossas vagas de Frontend. Se você estiver participando de um processo seletivo para nossa equipe, certamente em algum momento receberá este link, mas caso você tenha chego aqui "por acaso", sinta-se convidado a desenvolver nosso teste e enviar uma mensagem para nós no e-mail rafael.corazzi@orram.com.br.

Aqui na Orram Gestão nós aplicamos este mesmo teste para as vagas em todos os níveis, ou seja, um candidato a uma vaga de frontend júnior fará o mesmo teste de um outro candidato a uma vaga de frontend sênior, mudando obviamente o nosso critério de avaliação do resultado do teste.

Nós fazemos isso esperando que as pessoas mais iniciantes entendam qual o modelo de profissional que temos por aqui e que buscamos para o nosso time. Portanto, se você estiver se candidatando a uma vaga mais iniciante, não se assuste, e faça o melhor que você puder!

Primeiro vamos ver como voce responde com suas proprias palavras algumas perguntas técnicas 

1. Descreva a diferença entre um cookie, sessionStorage e localStorage.

2. Como você otimizaria os ativos/recursos de um site?

3. Qual é a diferença entre canvas e svg?

4. O que * { box-sizing: border-box; } faz? Quais são suas vantagens?

5. Qual é a diferença entre inline e inline-block?

6. O que é uma interface no TypeScript?

7. Você pode descrever a principal diferença entre o loop Array.forEach() e os métodos Array.map() e por que você escolheria um em vez do outro?

8. Explique Function.prototype.bind.

9. Qual é a diferença entre == e ===?

10. Quais são as diferenças entre as variáveis criadas usando let, var ou const?

O Projeto sera um analisador de variacoes entre moedas . 

Faça uma tela , aonde seja possivel o usuário escolher entre 2 moedas. seja Real/Dolar , Dolar/Real, Yen/Dolar , Yen/Real ao clicar no botao analisar o sistema ira busca na api uma variacao de 15 dias 

e em uma lista vai mostrar todas as variacoes da moeda nos 15 dias , e em um tabela ao lado mostrar as 5 maiores variacoes e qual foi a porcentagem da variacao entre elas 

um mock da tela

![Hello World](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEYAAAAUCAAAAAAVAxSkAAABrUlEQVQ4y+3TPUvDQBgH8OdDOGa+oUMgk2MpdHIIgpSUiqC0OKirgxYX8QVFRQRpBRF8KShqLbgIYkUEteCgFVuqUEVxEIkvJFhae3m8S2KbSkcFBw9yHP88+eXucgH8kQZ/jSm4VDaIy9RKCpKac9NKgU4uEJNwhHhK3qvPBVO8rxRWmFXPF+NSM1KVMbwriAMwhDgVcrxeMZm85GR0PhvGJAAmyozJsbsxgNEir4iEjIK0SYqGd8sOR3rJAGN2BCEkOxhxMhpd8Mk0CXtZacxi1hr20mI/rzgnxayoidevcGuHXTC/q6QuYSMt1jC+gBIiMg12v2vb5NlklChiWnhmFZpwvxDGzuUzV8kOg+N8UUvNBp64vy9q3UN7gDXhwWLY2nMC3zRDibfsY7wjEkY79CdMZhrxSqqzxf4ZRPXwzWJirMicDa5KwiPeARygHXKNMQHEy3rMopDR20XNZGbJzUtrwDC/KshlLDWyqdmhxZzCsdYmf2fWZPoxCEDyfIvdtNQH0PRkH6Q51g8rFO3Qzxh2LbItcDCOpmuOsV7ntNaERe3v/lP/zO8yn4N+yNPrekmPAAAAAElFTkSuQmCC)
Acessando as APIS 

Lista as moedas 

https://economia.awesomeapi.com.br/json/available/uniq

Legendas

| key  | Label |
| ------------- | ------------- |
| bid  | bid  |
| ask  | Venda  |
| bid  | bid  |
| varBid  | Variação  |
| bid  | bid  |
| pctChange  | Porcentagem de Variação  |
| high  | high  |
| low  | Mínimo  |



O que nós esperamos do seu teste
 * Ver na solução a utilização de um framework da sua escolha, mas por aqui utilizamos o ReactJS. Utilize o framework da melhor forma possível (metodologia/estrutura). Escolha a versão do ecmascript que lhe agrade
 * Tambér ver a utilização de dependency managers (npm, webpack)
 * Automação de tasks com gulp, grunt ou outra ferramenta de sua escolha (Não obrigatorio para Trainne/Estagiario)
 * Um HTML escrito da maneira mais semântica possível (HTML5/5.1)
 * CSS3/4 - Com um pre processador de CSS (a escolha fica a seu critério, mas por aqui utilizamos SASS) (Não obrigatorio para Trainne/Estagiario)
 * layout responsivo

Dicas construtivas 

O que não fazer

* Descobrir que não foi você quem fez seu teste
* Ver commits grandes, sem muita explicação nas mensagens em seu repositório
* Encontrar um um commit com as dependências de NPM e do Bower


O que avaliaremos de seu teste

* Histórico de commits do git
* As instruções de como rodar o projeto
* Organização, semântica, estrutura, legibilidade, manutenibilidade do seu código
* Alcance dos objetivos propostos
* Adaptação mobile (layout responsivo)
* Componentização e extensibilidade dos componentes Javascript