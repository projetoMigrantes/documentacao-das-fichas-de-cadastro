## Documentação das Fichas de Cadastro de Instituições e Migrantes

### Introdução

Esta documentação apresenta a análise das fichas de cadastro realizada pelos representantes do frontend e backend. Avaliamos quais dados já estão disponíveis no banco de dados, quais serão incluídos na aplicação, e aqueles que optamos por não inserir, levando em consideração a quantidade de membros na equipe e o tempo disponível para o desenvolvimento. 

Além disso, devido à ausência de orçamento para a hospedagem, é inviável adicionar muitas informações neste estágio. Estamos utilizando uma hospedagem gratuita, que impõe limites de armazenamento, o que reforça a necessidade de priorizar apenas os dados essenciais para garantir a funcionalidade da aplicação sem comprometer a performance.

---

#### 1\. Fichas de Cadastro de Instituições 

*   **Nome da Instituição**;
    
*   **CNPJ**;
    
*   **Responsável pelo cadastro da instituição**
    *   Nome Completo;
    *   Cargo;
    *   Setor;
    *   Função.
        
*   **ID do tipo de instituição**
    *   Agência Governamental;
    *   Delegacia de Migração;
    *   Centro de Atenção;
    *   Sociedade Civil Organizada;
    *   Organização Internacional;
    *   Instituição Religiosa;
    *   Instituição de Ensino;
    *   Procuradoria / Defensoria Pública;
    *   Tradutores Juramentos;
    *   Outros.
        
*   **Descrição da Instituição** (sobre a missão e o foco da instituição)
    *   Português;
    *   Espanhol;
    *   Francês;
    *   Inglês.
        
*   **Endereço**
    *   CEP;
    *   Cidade;
    *   Estado;
    *   Logradouro; 
    *   Bairro.
        
*   **Endereço complemento**
    *   Complemento;
    *   Ponto de Referência; 
    *   Número.
        
*   **Contato**
    *   Telefone Principal;
    *   Telefone Secundário;
    *   E-mail de contato;
    *   Site (não obrigatório);
    *   Redes Sociais
        *   Instagram.
            
*   **Horário de Funcionamento**
    *   Dias e Horários de Atendimento
        *   Presencial ou Online;
        *   Ordem de Chegada ou Hora marcada;
            
*   **Idiomas Falados pela Equipe**
    *   Primeira Língua;
    *   Segunda Língua;
        
*   **Critérios de Elegibilidade**  → Essa opção estará no **Manual do Migrante**.
    
*   **População Alvo** (Principal grupo atendido)
    *   Migrantes;
    *   Refugiados;
    *   Apátridas;
    *   Vítimas de Tráfico de Pessoas;
    *   Vítimas de Trabalho Escravo;
    *   Brasileiros Retornados;
    *   Mulheres;
    *   Crianças;
    *   Trabalhadores;
    *   LGBT+;
    *   Famílias Monoparentais;
    *   População Indígena;
    *   _Comunidade de Nacionalidade Especifica._
    *   Outro. 
        
*   **Serviços Oferecidos** (Múltipla Escolha)
    *   Apoio Legal e Jurídico;
    *   Orientação e Informação;
    *   Apoio Social e Psicológico;
    *   Capacitação Profissional;
    *   Apoio à Saúde;
    *   Intermediação de Emprego;
    *   Apoio à Educação;
    *   Apoio à Habitação;
    *   Apoio a Empreendedores e Empreendedorismo;
    *   Serviços Gerais de Integração
    *   Outros Serviços.
        
        _**Obs: Colocar o que cada serviço significa no Manual do Migrante.**_
        
*   **Custos dos Serviços**
    *   Serviço Gratuito? Sim (True) ou Não (False);
    *   Decimal (Valor do serviço);
    *   Descrição das taxas ou custos associados ao serviço.
        
*   **Autorização e Consentimento**
    *   Autorização para Compartilhamento de Informações
    *   Ex: **Concordo em compartilhar estas informações no aplicativo para visibilidade da nossa instituição.**
        

---

**2\. Fichas de Cadastro de Migrantes**

*   **Nome Completo**
    
*   **Nome Social**
    
*   **Data de Nascimento**
    
*   **Idioma de Preferência** 
    
*   **Data de Entrada no Brasil**
    
*   **Motivo da Imigração**
    
*   **Documento de Identificação** (Somente um documento)
    *   Tipo do Documento
    *   Identificação do Documento
        
*   **Endereço Atual no Brasil**
    *   CEP;
    *   Cidade;
    *   Estado;
    *   Logradouro; 
    *   Bairro.
        
*   **Endereço complemento**
    
    *   Complemento;
    *   Número.
    
*   **E-mail**
    
*   **Telefone**
    *   Número de WhatsApp? Sim (True) ou Não (False)
        
*   **Autorização e Consentimento**
    *   Autorização para Compartilhamento de Informações
    *   Ex: **Concordo em compartilhar minhas informações no aplicativo para visibilidade do meu perfil.**
        
*   **Gênero**
    *   Feminino;
    *   Masculino;
    *   Não-binário;
    *   Transfeminino;
    *   Transmasculino;
    *   Agênero;
    *   Gênero Fluido;
    *   Outro;
    *   Prefiro Não Informar.
        
*   **Escolaridade** (Nível Formal Concluído)
    *   Ensino Fundamental;
    *   Ensino Médio;
    *   Superior;
    *   Pós-graduação;
    *   Outro;
    *   Tem documentos originais? Sim (True) ou Não (False);
    *   Tem cópia do documento? Sim (True) ou Não (False);
    *   Completo ou Parcial;
        
*   **Status Migratório**
    
*    **Possui Necessidades Especiais?**  Sim (True) ou Não (False).
    
*   **Acesso a Programas Sociais oferecidos pelo Governo Brasileiro**     
    *   Cadastro Único
    *   Bolsa Família / Auxílio Brasil
    *   Aposentadoria / Benefício de Prestação Continuada (BPC)
    *   Outro (especificar)
