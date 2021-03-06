# Curso de Extreme Programming - DevMedia

## 0 - Introdução

Software é feito em ciclos/iterações. O feedback é essencial e as mudanças devem ser abraçadas.

## 1 - Engenharia de Software

### Agile:
	- Indivíduos e interações mais que processos e ferramentas
	- Software em funcionamento mais que documentação abrangente
	- Colaboração com o cliente mais que negociação de contratos
	- Responder a mudanças mais que seguir um plano

### Objetivos:
	- Reduzir o custo de mudanças
	- Entregar versões do software funcionando o mais rápido possível
	- Enxugar o processo de desenvolvimento e o próprio software em si

## 2 - Valores

### Simplicidade:
	- Sempre prezar pela solução mais simples possível para as funcionalidades do sistema
	- O sistema deve até omitir certas funcionalidades para garantir a sua Integridade Conceitual
	- Evitar generalizações, especulações e otimizações prematuras (OverEngineering)
	- Desenvolver funcionalidades apenas a medida que elas se tornam necessárias
	- Manter a simplicidade através de refatoração, reusabilidade de código, práticas de orientação à objetos e testes

### Feedback:
	- O Cliente analisa o sistema para aprovar o que foi feito ou demandar correções
	- O Cliente realimenta os desenvolvedores com informações, baseadas em observações sobre o que já foi desenvolvido, que permitam a evolução do software
	- O Desenvolvedor deve informar ao Cliente o custo, o prazo e o risco da implementação de determinada funcionalidade (viabilidade técnica do que está sendo pedido)
	- Os feedbacks devem ser dados o mais rápido possível, para aumentar as chances de aprendizado

### Comunicação:
	- Fornece meios para que prioridades, equívocos e detalhes sejam tratados da melhor forma possível
	- É essencial que Cliente e Desenvolvedor se comuniquem para tirar dúvidas e alinhar o que deve ser feito
	- Deve ser eficiente (rápida) e eficaz (resultado satisfatório)

### Coragem e Respeito:
	- São essenciais para o sucesso do projeto, em todos os sentidos
	- Coragem para praticar as atividades propostas pela XP

## 3 - Princípios

### Auto-semelhança:
	- Reúso de soluções/padrões
	- Testes, Histórias, Refatoração, Design Patterns

### Benefício Mútuo:
	- As práticas realizadas devem beneficiar a todos (cooperação)
	- Pair Programming, Código Compartilhado, Testes Unitários, Integração Contínua

### Diversidade:
	- Interdisciplinaridade é fundamental para criar soluções criativas e inovadoras
	- Pair Programming, Código Compartilhado, Cliente presente

### Economia:
	- Foco no Retorno Sobre Investimento
	- TDD, Releases frequentes

## 4 - Práticas

### Cliente Participativo:
	- Cliente + Equipe = Sucesso
	- Menos dúvidas, retrabalho e falhas
	- Mais feedback, segurança e confiança
	- Entregas no prazo
	- Sistema mais simples
	- Equipe motivada e cliente satisfeito

### Planing Game:
	- Elaborar a visão inicial do sistema
	- Coletar as User Stories:
		- Devem possuir Testes de Aceitação, para validar a solução que foi implementada
		- Serão quebradas em tarefas menores, para facilitar a implementação
		- Devem ser estimadas, para avaliar quanto tempo/esforço irão demandar
	- Planejar as releases:
		- Dividir o projeto, para que possa evoluir através da entrega de módulos incrementais com tempos idênticos
		- Dividir a primeira release em Iterações
	- Selecionar as User Stories que entrarão nas iterações
	- Ao final de cada iteração:
		- Fazer testes
		- Receber feedbacks
		- Planejar a próxima iteração, reavaliando user stories, estimativas e prazos
	- Ao final de cada release:
		- Fazer testes
		- Receber feedbacks
		- Entregar um produto funcional
		- Planejar a próxima release

### User Stories:
	- Meio onde o Cliente informar o que o sistema:
		- Deve e não deve fazer
		- Será e o que não será
	- Serve também como fonte de informação sobre o negócio e de insumo para testes

### Testes de Aceitação:
	- Servem para validar as User Stories
	- São descritas na visão do Cliente, a nível de interface de uso do sistema
	- Podem servir de extensões das User Stories também, por conterem informações e regras de negócio
	- Estrutura:
		- Cenário => Operação => Verificação
	- Podem ser automatizados

### Estimativas:
	- Juntar Cliente e Desenvolvedores para avaliarem a complexidade de cada US
	- Usar pontos (dias ou semanas) como unidade de medida
	- US grandes podem ser divididas em tarefas

### Metáforas:
	- Auxiliam na comunicação entre Negócio e Tecnologia
	- Paralelo com o conceito de Linguagem Ubíqua

### Releases:
	- Cada release é dividida em iterações
	- Desenvolvimento incremental e enxuto
	- Cada uma entrega parte do software funcionando e testado

### Iterações:
	- Cada uma é formada por User Stories
	- Podem ter 1 ou 2 semanas
	- 1 dia para planejar, 1 para entregar, o resto para implementar

### Stand Up Meeting:
	- Reuniões diárias, curtas e feitas em pé
	- Semelhante a daily do Scrum

### Pair Programming:
	- Redução de bugs
	- Discussões levam à implementação de soluções melhores
	- Pair pressure, mais produtividade

### Design Simples:
	- Dúvidas e suposições geram designs complexos e difícies de mudar
	- Permite a realização de alterações de forma relativamente fácil
	- Decisões podem ser procrastinadas
	- Fazer o necessário para o momento
	- Só adicionar complexidade se for realmente necessário
	- Regras de Kent Back:
		- Códigos e Testes devem expressar juntos o que o desenvolvedor deseja comunicar
		- Sem duplicação de código nem comentários
		- Menor número possível de Classes e Métodos
	- Simples, não mal feito

### Código Coletivo:
	- Todos têm acesso ao código produzido por todos
	- Ajuda a manter a qualidade alta

### Refatoração:
	- Essencial para aumentar a qualidade do código
	- Mantém a entropia constante
	- Melhora de performace

### Código Padronizado:
	- Possibilita a expressão de intensões/ideias de forma clara e objetiva
	- Agiliza o entendimento do que o código faz
	- Code Style automatizado, evitar discussões

### Design Patterns:
	- Dado um problema, dentro de um contexto específico
	- Um Pattern é uma solução para esse problema
	- Possui partes boas e ruins (trade-offs)
	- Pode servir de base para resolução de problemas similares

### Evitar Débitos Técnicos:
	- Utilizar conceitos de:
		- Arquitetura de Software
		- Design Patterns, Orientação à Objetos
		- DDD, TDD
	- Testar e refatorar é essencial

### Integração Contínua:
	- Quanto mais demorado o merge, pior
	- Integrar o código constantemente
	- Build e testes automatizados
	- Git, Jenkins, Hudison...

### Test Driven Development:
	- Escrever os testes que falham
	- Escrever código para passar nos testes
	- Refatorar

### Velocidade Sustentável:
	- Semana de 40h
	- Horas extras somente em momentos excepcionais

### Entrega de Iterações:
	- O Cliente deve executar os Testes de Aceitação e validar a correta implementação das US
	- É um momento de aprendizado para todos, via feedbacks

### Entrega de Releases:
	- Deploy do sistema em produção
	- Virão feedbacks dos usuários
	- Acarreta em diversas atividades para sustentação

## 5 - Papéis e Responsabilidades

### Gerente de Projeto:
	- Defende, promove e tem uma visão holística sobre a equipe
	- Incentiva a utilização das práticas da XP
	- Cuida da logística envolvida no desenvolvimento do projeto

### Desenvolvedor:
	- Personagem central na XP
	- Analisa, modela, projeta, planeja e implementa o sistema
	- Testa e faz intergrações
	- Refatora e corrige

### Analista de Testes:
	- Perito em testes
	- Garante a qualidade e a corretude do sistema

### Redator Técnico:
	- Faz e atualiza a documentação do software
	- Faz código e documentação refletirem um ao outro

### Coach:
	- Change your mindset

### Narradores:
	- Pessoas com conhecimento de negócio
	- Escrevem US e Testes de Aceitação

### Aprovadores:
	- Validam as US, via testes

### Planejadores:
	- De releases, iterações e US

## 6 - Outros Aspectos

### Ambiente de Trabalho:
	- Deve ser propício para facilitar as práticas da XP

### Documentação:
	- Só o essencial

### Contratos:
	- De escopo aberto

### Métricas:
	- Código funcionando, gerando e entregando valor

### Projetos que não podem usar XP:
	- Aqueles que envolvem licitações
	- Software crítico, aviões, reatores...

### Quando não tem cliente:
	- Alguém deve ter conhecimento de negócio suficiente para fazer o papel do cliente

### Cuidados antes e no início do projeto:
	- Focar nos fundamentos e nas práticas a longo prazo
