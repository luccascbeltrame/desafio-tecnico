# Teste SRE / DevOps Engineer - EMPRESA X

Esse é o teste para SRE / DevOps Engineer para XXXX.
Ele consiste em avaliar seu conhecimento em Infraestrutura como Código, Docker e sua lógica para resolver problemas.

## Desafio

O desafio consiste em três partes, você pode organizar o repositório da maneira que achar melhor.

### Parte 1 - Infraestrutura como Código

1. Utilizando Terraform, crie um módulo que provisione instâncias no GCP e que exponha a porta 1337 para um IP ou range de IPs que deverá ser recebido via input;
2. Utilize outputs para imprimir o IP público e o hostname da instância;
3. Documente como utilizar o módulo.

### Parte 2 - Kubernetes

1. Crie uma imagem Docker para a aplicação que está em `app-base`;
2. Com a imagem criada, crie manifestos/definitions para fazer deploy dessa aplicação em cluster Kubernetes;
3. Essa aplicação precisa ser acessível pela internet na porta 443.

Desafio Hard: Se sentir confortavel implemente pequenas melhorias no codigo.

### Parte 3 - Troubleshooting

1. Baixe e rode a imagem docker XXXX/sre-challenge;
2. Documente os passos que você realizou para tentar solucionar o desafio.

## Começando

- Crie uma nova branch com o nome que desejar, você ira abrir uma Pull Request ao finalizar o teste;
- Garanta que você esteja utilizando no mínimo Terraform 0.12.x;
- Você pode utilizar uma conta no GCP e usar o free tier para testar sua implementação;
- Tenha em mente princípios de alta disponibilidade, elasticidade e segurança.

## O que estamos procurando

Prezamos por boas práticas no desenvolvimento e implantação, e estamos buscando um profissional que se encaixe nesse perfil, que não somente mantenha os processos existentes em funcionamento, mas que traga novas idéias, ferramentas e que adore resolver problemas.

## Entrega do teste

Não é necessário provisionar nenhuma infraestrutura, nos enviar IPs ou SSH keys. Queremos avaliar sua proficiência com Terraform, Docker, Kubernetes e sua lógica na solução do desafio. Ao final do teste, você deverá abrir uma Pull Request.

Caso tenha dúvidas, basta abrir uma issue e responderemos assim que possível.