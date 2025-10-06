```mermaid
    gantt
    title Sistema de Cadastro de Empresas
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Preparação
    Levantamento de Requisitos       :a1, 2025-10-05, 7d
    Documentação Funcional           :a2, after a1, 7d

    section Design
    Rascunho de Telas                :a3, after a2, 7d
    Layout Final do Sistema          :a4, after a3, 7d

    section Desenvolvimento
    Configuração do Ambiente         :a5, after a4, 7d
    Criação do Banco de Dados        :a6, after a5, 7d
    Módulo de Login                  :a7, after a6, 7d
    CRUD de Empresas                 :a8, after a7, 7d
    Upload de Logotipo               :a9, after a8, 7d
    Relatórios PDF/Excel             :a10, after a9, 7d
    Painel Administrativo            :a11, after a10, 7d

    section Testes e Implementação
    Testes unitários e de integração     :a12, after a11, 7d 
    Testes de usabilidade                :a13, after a12, 7d
    Implantação final e Entrega          :a14, after a13, 7d 

```
