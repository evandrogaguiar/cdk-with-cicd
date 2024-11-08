# AWS CDK com Integração Contínua (CICD)

Neste projeto, utilizei o AWS CDK para criar um bucket onde armazenamos os arquivos de uma aplicação web simples (Vite + React)

Também criamos uma distribuição do CloudFront que tem como origem nosso Bucket.

## GitHub Actions

Após o projeto pronto, foi a vez de automatizar criando um workflow do Github, que pode ser visto no arquivo

* `./github/workflows/py-dev.yml`

## Explicação

Basicamente, toda vez que houver alguma alteração no projeto (push na branch master), a pipeline será iniciada, fazendo a alteração direto em nossa Stack.

* `GitHub Actions` For documentation [GitHub Actions](https://docs.github.com/pt/actions)

Enjoy!