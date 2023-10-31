## Revolução das letras: Requisitos e Orçamento

### Cálculo do Valor da Hora

- R$ 55/hora: Este valor foi calculado considerando um salário base mensal, dividido por 22 dias úteis e por 8 horas diárias, e dobrado para considerar o trabalho nos finais de semana (100% de acréscimo).

### Requisitos Funcionais (Obrigatórios)

#### Responsividade: Quais dispositivos que eu posso acessar o site.

- Dispositivos: Acesso via Desktop com resoluções de 1280x720 até Ultrawides.

#### Acesso

- **Front-end (Interface)**
    - Criação da tela de Acesso
        - Design da Tela: 4 horas (R$ 220)
        - Implementação da Tela no Site: 10 horas (média) (R$ 550)
- **Back-end (Lógicas de Negócio)**
    - Criação do modelo e banco de dados (2 horas) (R$ 110)
    - Autenticação por Token de Acesso: 5 horas (média) (R$ 275)

#### Usuários

- **Front-end (interface)**
    - Listagem de Usuários
        - Design de Tela: 2 horas (R$ 110)
        - Implementação de Tela no Site: 5 horas (média) (R$ 275)
        - Botão para Criação de Novos Usuários: Incluso na implementação
        - Modal ou Tela para Adicionar Novo Usuário: 2 horas (R$ 110)
- **Back-end (Lógicas de Negócio)**
    - Criação do Modelo e Banco de Dados: 2 horas (R$ 110)
    - Listagem de Usuário por Acesso: 5 horas (média) (R$ 275)

#### Trilha

- **Front-end**
    - Obrigatoriedade de reutilização do mapa estático: 5 dias (40 horas) (R$ 2.200)
        - Disposição dos elementos gráficos (botões) dentro do mapa.
        - Usabilidade do cliente.
    - Tela que acopla Jogos/Vídeos: 3.5 dias (média) (28 horas) (R$ 1.540)
        - Botão de próximo passo ou passo anterior.
        - Voltar para o menu.
        - Pontuação simples: passando para o próximo passo.
- **Back-end**
    - Lógicas de Pontuação e Progresso: 4 dias (32 horas) (R$ 1.760)
        
#### Jogos

- **Jogo do ditado:** 3.5 dias (média) (28 horas) (R$ 1.540)
    - Mostrar imagem e botão que fala o nome do objeto.
    - Botão que mostra o nome escrito do objeto. 
    - Nesse meio tempo a criança: deve escrever o que viu ou o que escutou.
- **Jogo de navinha:** 30 dias (média) (240 horas) (R$ 13.200)
    - Parte visual:
        - Nave
            - Recebendo dano
            - Movimentando
        - Tiro
        - Meteoro
            - Inteiro, quebrando.
        - Fundo
    - Parte lógica do jogo:
        - Lógica de movimentação da nave.
            - Lógica do tiro da nave
                - Movimentação
                - Impacto com o meteoro
        - Lógica de criação de meteoro
            - Movimento automático dos meteoros.
            - Lógica de impacto meteoro-nave
        - Criação das letras
            - Criação de aleatoriedade o aparecimento dentro do cenário.
            - Lógica de capturar as letras com a nave
        - Vida da nave (3 vidas)
        - O que acontece quando a gente pega uma letra na ordem errada -> Perde vida
        - Lógica para verificar se a palavra está formada.
        - Lógica para saber quando perdeu.   

- **Jogo de digitação:** 6 dias (média) (48 horas) (R$ 2.640)
    - Partes visuais:
        - Palavra
        - Teclado, mostrando qual letra devo apertar.
        - Mãos: esquerda e direita, mostrando qual mão e qual dedo eu devo utilizar.   
    - Logica
        - Verificar se a palavra foi escrita
        - A cada letra inserida trocar elementos visuais: letra do teclado e mão.
    
- **Jogo da mémoria:** 2 dias (16 horas) (R$ 880)
    - Partes visuais: 
        - Fundo da carta
        - Parte da frente
    - Logicas:
        - Acerto, mantém virado para frente.
        - Erro, retorna para o fundo.


#### Servidor e Serviços

- Configuração e Manutenção: 4 dias (média) (32 horas) (R$ 1.760)
- Orçamento de Custos dos Serviços: 1.5 dias (média) (12 horas) (R$ 660)

### Tempo Estimado para Cada Parte do Projeto:

- **Acesso (Front-end + Back-end):** 14 horas
- **Usuários (Front-end + Back-end):** 7 horas
- **Trilha (Front-end + Back-end):** 72 horas (9 dias)
- **Jogos:**
    - **Ditado:** 28 horas (3.5 dias)
    - **Navinha:** 240 horas (30 dias)
    - **Digitação:** 48 horas (6 dias)
    - **Memória:** 16 horas (2 dias)
- **Servidor e Serviços:** 44 horas (5.5 dias)
- **Somando o Tempo Total:** 14 + 7 + 72 + 28 + 240 + 48 + 16 + 44 horas = 369 horas

Convertendo para dias (considerando 8 horas de trabalho por dia):
369 horas / 8 horas ≈ **46.125 dias**

Portanto, o projeto levaria aproximadamente 46 dias para ser concluído, considerando a estimativa média de tempo para cada tarefa e uma jornada de trabalho de 8 horas por dia.

Total Estimado: **R$ 29.620**

### Requisitos não Funcionais (Não Obrigatórios)

#### Responsividade

- **Acesso para Celulares e Tablets:** Este item seria tratado como uma melhoria futura.

#### Acesso

- **Quantidade de Usuários:** Este item deve ser discutido mais detalhadamente para estabelecer uma limitação, se necessária.

### Trilha

- **Monitoramento de Atividades:** Implementação de lógicas para garantir que o usuário realmente finalizou o vídeo ou jogo e evitar pontuação repetida.

#### Usuários

- **Segurança e Privacidade:** Implementação de medidas para garantir a segurança dos dados do usuário e sua privacidade.

#### Jogos

- **Jogo da Forca e Anagrama:** Estes jogos podem ser adicionados como melhorias futuras, considerando o escopo e o orçamento disponível.

#### Testes: Planejar e alocar tempo para testes extensivos em todas as partes do sistema, especialmente nos jogos.

#### Feedback do Usuário: Incluir uma fase de teste com usuários reais para coletar feedback sobre a usabilidade e possíveis melhorias.


## Notas
- É importante observar que os tempos estimados para as tarefas são médias, e podem variar conforme a complexidade do projeto e a equipe de desenvolvimento.
- O valor total é uma estimativa e pode ser ajustado conforme as necessidades específicas do projeto e acordos com a equipe de desenvolvimento.
- Os requisitos não funcionais listados, incluindo a responsividade para celulares e tablets, assim como outras considerações de acesso, segurança, e funcionalidades adicionais de jogos, não estão incluídos no orçamento inicial. Planejamentos e orçamentos adicionais seriam necessários para abordar esses aspectos.
- A manutenção contínua do site após a conclusão e entrega do projeto não está inclusa no valor final orçado. Acordos específicos para manutenção e suporte técnico contínuo podem ser estabelecidos à parte.