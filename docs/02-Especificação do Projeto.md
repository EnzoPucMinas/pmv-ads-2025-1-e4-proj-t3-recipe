# Especificações do Projeto

## Personas

### Mariana Souza, 27 anos

![Imagem de Mariana](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-2-e3-proj-mov-t2-delivery/blob/main/docs/img/PersonaMariana.jpg)

Profissão: Criadora de Conteúdo Culinário.<br>
Local: São Paulo, Brasil.<br>
Tecnologias:

- Smartphone;
- Laptop;
- Câmera para gravação.<br>

Objetivos:

- Criar conteúdo dinâmico e engajador sobre receitas;
- Fornecer versões resumidas dos vídeos para seguidores que buscam rapidez;
- Aumentar o engajamento nas redes sociais.<br>

Desafios:

- Editar vídeos de forma eficiente;
- Criar versões curtas sem perder informações essenciais;
- Manter a audiência engajada com conteúdo objetivo.<br>

Como o aplicativo pode ajudar:

- Gerar automaticamente resumos de vídeos com os principais passos da receita;
- Criar descrições organizadas para melhor indexação nas redes sociais;
- Automatizar a extração de ingredientes e tempos de preparo.

### Ricardo Lima, 35 anos

![Imagem de Ricardo](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-2-e3-proj-mov-t2-delivery/blob/main/docs/img/PersonaRicardo.jpg)

Profissão: Cozinheiro Autodidata.<br>
Local: Rio de Janeiro, Brasil.<br>
Tecnologias:

- Smartphone;
- Tablet.

Objetivos:

- Aprender receitas novas de forma rápida e prática;
- Evitar assistir a vídeos longos para extrair informações relevantes;
- Ter acesso a listas de ingredientes e tempos de preparo de forma organizada.<br>

Desafios:

- Encontrar informações rápidas sem assistir a vídeos completos;
- Acompanhar receitas enquanto cozinha sem precisar pausar o vídeo constantemente;
- Acessar resumos confiáveis e bem estruturados.

Como o aplicativo pode ajudar:

- Fornecendo resumos automáticos dos vídeos com os passos principais;
- Criando listas automáticas de ingredientes;
- Disponibilizando tempos de preparo de maneira clara.

## Histórias de Usuários

| EU COMO... `PERSONA`                    | QUERO/PRECISO ... `FUNCIONALIDADE`                    | PARA ... `MOTIVO/VALOR`                                      |
| --------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------ |
| Criadora de conteúdo culinário          | Gerar automaticamente um resumo de meus vídeos        | Aumentar engajamento e facilitar a distribuição do conteúdo. |
| Cozinheiro autodidata                   | Obter rapidamente os ingredientes e passos da receita | Economizar tempo e seguir o preparo sem interrupções.        |
| Estudante universitário                 | Ter acesso a receitas curtas e objetivas              | Preparar pratos rápidos no dia a dia.                        |
| Pessoa com pouca experiência na cozinha | Receber um guia simplificado das receitas             | Aprender a cozinhar de forma mais intuitiva.                 |
| Profissional ocupado                    | Conseguir um resumo rápido das receitas               | Cozinhar rapidamente sem assistir ao vídeo inteiro.          |

## Modelagem do Processo de Negócio

### Análise da Situação Atual

Atualmente, muitas pessoas utilizam vídeos online para aprender novas receitas. No entanto, esses vídeos costumam ser longos e contêm informações desnecessárias para quem deseja apenas seguir o passo a passo de forma rápida.

### Descrição Geral da Proposta

A plataforma desenvolvida utilizará Inteligência Artificial para gerar resumos automáticos de vídeos culinários. Com isso, os usuários poderão acessar rapidamente os ingredientes, tempos de preparo e os passos principais da receita, sem precisar assistir ao vídeo completo.

### Processo de Extração de Informação

1. O usuário faz upload do vídeo de uma receita.
2. A IA analisa o áudio e identifica os ingredientes, tempos e modos de preparo.
3. Um resumo é gerado automaticamente e apresentado ao usuário.

## Indicadores de Desempenho

| Indicador                            | Objetivo                       | Descrição                                                  | Cálculo                                            | Fonte Dados      | Perspectiva |
| ------------------------------------ | ------------------------------ | ---------------------------------------------------------- | -------------------------------------------------- | ---------------- | ----------- |
| Tempo médio para gerar um resumo     | Melhorar eficiência do sistema | Mede o tempo desde o upload até a geração do resumo        | Tempo total / número de uploads                    | Logs do sistema  | Eficiência  |
| Precisão da extração de ingredientes | Melhorar a precisão da IA      | Mede quantos ingredientes foram corretamente identificados | Ingredientes corretos / ingredientes totais \* 100 | Avaliação manual | Qualidade   |
| Taxa de uso da plataforma            | Avaliar a adoção da solução    | Mede a quantidade de usuários ativos mensais               | Usuários ativos / total de cadastros \* 100        | Dados do sistema | Engajamento |

## Requisitos

### Requisitos Funcionais

| ID     | Descrição do Requisito                   | Prioridade |
| ------ | ---------------------------------------- | ---------- |
| RF-001 | Permitir upload de vídeos de receitas    | ALTA       |
| RF-002 | Gerar resumos automáticos dos vídeos     | ALTA       |
| RF-003 | Extrair ingredientes e tempos de preparo | ALTA       |
| RF-004 | Exibir resumos de forma organizada       | MÉDIA      |
| RF-005 | Permitir busca por resumos específicos   | MÉDIA      |

### Requisitos Não Funcionais

| ID      | Descrição do Requisito                           | Prioridade |
| ------- | ------------------------------------------------ | ---------- |
| RNF-001 | Suporte para dispositivos móveis                 | ALTA       |
| RNF-002 | Interface intuitiva e responsiva                 | ALTA       |
| RNF-003 | Processamento rápido de resumos                  | ALTA       |
| RNF-004 | Armazenamento seguro dos vídeos                  | MÉDIA      |
| RNF-005 | Compatibilidade com diferentes formatos de vídeo | MÉDIA      |

## Restrições

| ID  | Restrição                                                       |
| --- | --------------------------------------------------------------- |
| 01  | O projeto deve ser concluído em seis meses.                     |
| 02  | A IA deve suportar língua portuguesa.                           |
| 03  | A solução deve ser acessível em dispositivos móveis e desktops. |
