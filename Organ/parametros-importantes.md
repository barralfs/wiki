---
title: Parâmetros Importantes
description: 
published: true
date: 2026-02-26T17:57:07.339Z
tags: organ
editor: markdown
dateCreated: 2025-12-05T17:03:51.635Z
---

# Lista de Parâmetros de Configuração

Abaixo encontra-se a tabela com os parâmetros de configuração do sistema, seus valores padrões ou esperados e a respectiva descrição da funcionalidade.

| Parâmetro | Configuração / Valor | Descrição |
| :--- | :--- | :--- |
| **ABATER_DEVOLUCAO_IMPORTACAO_RECEITA_NF** | - | Faz com que a quantidade devolvida de um item seja abatida na hora de emitir nota fiscal daquela movimentação. |
| **ABRIR_PESQUISA_INSERIR_ITEM_RECEITA** | `N` | Desabilita a janela de pesquisa de produtos aparecendo automaticamente. |
| **ACAO_FINALIZAR_PEDIDO_COMPRA** | `STATUS` | Finaliza apenas o status do "Pedido de Compra". |
| **AcaoInicialCertificado** | `1`, `2` ou `3` | Força uma inicialização específica do certificado A3 no PDV. |
| **ALIQUOTA_CRED_ICMS_INDUSTRIALIZACAO** | `VALOR` | Define alíquota automática para CFOPs 5101, 6101, 5124, 6124, 5125 ou 6125. Outros CFOPs usam a padrão da empresa. |
| **ATIVAR_CONTROLE_LOTE_FISCAL** | `S` | Possibilita informar lotes de produtos fiscais (manual ou auto). Requer estoque por lote alimentado. |
| **BUSCAR_EAN_CADASTRO_PRODUTO** | - | Busca o código de barras do produto para preencher o campo GTIN da Nota Fiscal. |
| **BUSCAR_TRIBUTACAO_ENTRADA** | `S` | Considera as informações do grupo tributário para a entrada de Notas Fiscais. |
| **CODIGO_AJUSTE_C197_CRED_ICMS_SN** | Código | Define código padrão no SPED para NFs de fornecedores Simples Nacional com aproveitamento de crédito. |
| **CONSIDERAR_CREDITO_IMPOSTO_CUSTO_MEDIO** | - | Considera ou não o crédito ST nas operações de compra/despesa. |
| **CONSIDERAR_DESCONTO_BC_ICMS** | - | Refaz cálculos de impostos considerando o desconto na NF (processo variável por contabilidade). |
| **CONSIDERAR_DESCONTO_BC_ICMS_ST** | `N` | Refaz cálculos de impostos ST considerando o desconto na NF. |
| **CONSIDERAR_DESCONTO_IMPORTAR_OS_RPS** | - | Considera o desconto da Ordem de Serviço na importação para emissão do RPS. |
| **CONSIDERAR_LANCAMENTO_ESTOQUE_ULTIMA_COMPRA** | `S` ou `N` | Considera (`S`) ou desconsidera (`N`) o lançamento de estoque no 'Custo de Última Compra'. Se `N`, atualiza custo apenas se for o primeiro lançamento. |
| **ENVIAR_BOLETO_EMAIL_NFE** | `S` | Envia boleto junto com a NF por e-mail (Meio de pagamento deve ser 15 - Boleto Bancário). |
| **EXCLUIR_ICMS_BASE_CALC_PIS_COFINS** | `S` ou `N` | `S`: Abate ICMS da base de PIS/COFINS. `N`: Base de cálculo é o valor total. |
| **EXIBIR_CODIGO_AUX_ITEM_MOVIMENTO** | `S` | Exibe Código Auxiliar no lugar do Código em Vendas, Consignados e DAV. |
| **EXIBIR_CONTAS_TODAS_EMPRESAS** | - | Permite visualizar todas as 'Contas a Receber' em bancos multi empresa. |
| **EXIBIR_LOTE_DANFE** | `S` ou `N` | Exibe (`S`) ou Oculta (`N`) informações de lote na DANFE (se controle de lote fiscal estiver ativo). |
| **EXIBIR_TRIBUTOS_APENAS_CONSUMIDOR_FINAL** | - | Exibe tributos aproximados na NF. |
| **EXIBIR_FORM_RECEITA_FINALIZAR_ORDEM_SERVICO** | - | Finaliza O.S. sem exibir a tela de Vendas e Receitas para edição. |
| **EXIGIR_CATEGORIA_MOVIMENTACAO_PRODUTO** | `S` | Torna obrigatório 'Categoria Receita' e 'Categoria Despesa' no cadastro do produto. |
| **EXIGIR_CODIGO_BARRAS_PRODUTO_GRADE** | - | Valida e exige geração de código de barras para produtos com grade. |
| **FECHAR_COMANDA_SEM_ABRIR_TELA_RECEITA** | `N` | Abre a tela de Vendas e Receitas ao finalizar comanda (útil para inserir Créditos de Devolução). |
| **HABILITAR_ADIANTAMENTO_ORDEM_SERVICO** | `S` | Permite informar adiantamentos de pagamento em O.S. (botão direito). |
| **HABILITAR_CALCULO_MEDIDA_ITEM_MOVIMENTO** | - | Habilita botão "Medida" para cálculo de M³ (Qtd, Largura, Altura, Comprimento). |
| **HABILITAR_CANCELAR_COMANDA_FRONTSTORE** | `S` | Permite ao vendedor cancelar item na comanda. |
| **HABILITAR_COMANDA_FRONTSTORE** | `S` | Habilita uso de comandas no Frontstore. |
| **HABILITAR_CONFERENCIA_PEDIDO_FRONTSTORE** | `S` | Habilita conferência de pedidos no Frontstore. |
| **HABILITAR_CONTA_PAGAR_RECEBER_FISCAL** | - | Habilita tela de Contas a Pagar/Receber do módulo fiscal. |
| **HABILITAR_MULTI_SELECAO_COMANDA_FRONTSTORE** | `S` | Permite selecionar mais de um item por vez no FrontStore comandas. |
| **HABILITAR_ORDEM_SERVICO_FRONTSTORE** | `S` | Habilita o módulo de O.S. para o FrontStore. |
| **HABILITAR_PESQUISA_ESTOQUE_FRONTSTORE** | `S` | Habilita o módulo de pesquisa de estoque. |
| **HABILITAR_PESQUISA_PRECO_FRONTSTORE** | `S` | Habilita o módulo de pesquisa de preços. |
| **ID_GRUPO_PRODUTO_IGNORAR_CUPOM** | `idDoGrupo` | Produtos com este ID de grupo não serão exibidos no OrganPDV. |
| **ID_CONTA_FISCAL_BANCARIA** | `idConta` | Ao informar o identificador da conta bancária, o sistema gera automaticamente as parcelas para os seguintes pagamentos: Cartão de Crédito, Cartão de Débito, PIX Dinâmico e PIX Estático. |
| **IMPRIMIR_ITEM_COMANDA_ORGAN** | - | Define se o item inserido pelo Organ será impresso ou não. |
| **INFORMAR_NSU_VENDA_CARTAO_PDV** | - | Permite vincular NSU da maquininha nas operações fiscais (NF-e/NFC-e). |
| **INFORMAR_PESO_NF_MANUALMENTE** | - | Permite digitar Peso Bruto e Líquido na aba Transportes da NF. |
| **LISTA_ID_USUARIO_PRODUTO_CODIGO** | `idUsuario` | Impede pesquisa por nome na venda para o usuário listado, permitindo apenas campo 'Código'. |
| **NOME_CAMPO_CUSTOM_PRODUTO_1** | `Desc NF` | Descrição do campo Custom 1 será usada como nome do produto na NF-e. |
| **NUMERO_INICIAL_FATURA_LOCACAO** | `S` | Permite gerar fatura a partir de uma locação (botão direito). (Tabela CONFIG_EMPRESA). |
| **MODO_OPERACAO_DESPESA** | `P` ou `C` | `P`: Padrão. `C`: Caixa/Balcão (leitura de código salva e pula para próximo item automaticamente). |
| **OCULTAR_DADOS_CABECALHO** | `S` | Oculta cabeçalho nos relatórios OFICIAIS de movimentações. |
| **OrdenarImpressaoItem** | `S` | Imprime itens em ordem alfabética (Config DAV). |
| **PERMITIR_ALFA_NUMERICO_COMANDA** | `S` | Permite comandas com letras e números. |
| **PERMITIR_CADASTRO_PESSOA_CNPJ_CPF_REPETIDO** | `S` | Permite múltiplos cadastros com mesmo CPF/CNPJ. |
| **PERMITIR_DESCONTO_PARCELA_RECEITA** | `S` | Permite qualquer desconto em parcelas, ignorando limites de Venda/Cliente. Também usado na Pré-Venda. |
| **PERMITIR_EDITAR_CLIENTE_NOTA_FISCAL_IMPORTADA** | `S` | Permite alterar o cliente após importar Venda para NFe (se cliente for Padrão). |
| **PERMITIR_FINALIZAR_ORCAMENTO_SEM_RECEITA** | - | Permite finalizar Pedido de Venda parcialmente finalizado (somente status). |
| **PERMITIR_ITEM_REPETIDO_PEDIDO** | `S` | Permite produtos repetidos em pedidos de venda no Frontseller. |
| **PERMITIR_MOVIMENTAR_CHEQUE_SEM_ACERTO** | `S` | Movimenta cheque pelo botão direito sem necessidade de acerto. |
| **PERMITIR_QUANT_SUPERIOR_FINALIZAR_PEDIDO_VENDA** | - | Trava ou libera finalização de Pedido de Venda conforme quantidade. |
| **PERMITIR_REIMPRESSAO_RECEITA** | `N` ou `S` | `N`: Bloqueia reimpressão de Venda/Receita. `S`: Permite. |
| **PRODUTO_SINCRONIZAR_MOBILE_PADRAO** | `N` | Define padrão 'Sincronizar Mobile' e 'Marketplace' como marcado no cadastro. |
| **REQUERIDO_ORCAMENTO_CAMPO_CUSTOM_1** | `S` | Exige preenchimento do campo customizado (1 ao 18) no orçamento. |
| **SALVAR_ARQUIVO_XML_NFE_AUTORIZADA** | `S` | Salva XMLs autorizados em `Organ\NFe\XMLAutorizado\`. |
| **SOMAR_QUANTIDADE_RECEITA** | `S` | Soma quantidades e exibe total em Vendas, Compras e Balanço. |
| **SUGERIR_PRECO_ITEM_DESPESA** | `S` | Preenche custo unitário ao inserir item em Compras e Despesas. |
| **TabelaPreco** | `(Vazio)` ou ID | No PDV, define tabela de preço. Vazio puxa preço padrão. |
| **ULTIMA_PESQUISA_PEDIDO_FRONTSELLER** | Data/Hora | Define data da última pesquisa na nuvem. Intervalo mínimo de 1 min. |
| **UTILIZAR_CAPICOM** | `S` | Configura uso correto do CAPICOM (Tabela CONFIG_EMPRESA). |
| **UTILIZAR_CODIGO_AUXILIAR_ITEM_NOTA_FISCAL** | - | Puxa código auxiliar ou EAN para a Nota Fiscal. |
| **UTILIZAR_DATA_ENTREGA_PARCELAMENTO_RECEITA** | `S` | Parcelamento baseia-se na data de entrega, não na emissão. |
| **UTILIZAR_DATA_FIXA_CAIXA_DIARIO** | `S` | Utiliza o Caixa Antigo. |
| **UTILIZAR_DATA_FIXA_CAIXA_DIARIO** | `N` | Mantém o funcionamento do Caixa Atual. |
| **ValorFrete** | `VALOR` | Insere valor de frete automático em vendas no DAV. |
| **VERIFICAR_SITUACAO_CLIENTE_ORCAMENTO** | `S` | Avisa se cliente no Orçamento possui parcelas vencidas. |
| **VINCULAR_PARCELA_NOTA_FISCAL** | `S` | Edita número das parcelas do Contas a Receber conforme número da NFe. |
| **VISUALIZAR_DANFE_APOS_AUTORIZACAO** | `S` | Exibe a DANFE após transmissão da nota. |
| **ZERAR_TRIBUTOS_IMPORTAR_XML_SN** | - | Zera tributos de ICMS na importação de NF entrada para Simples Nacional. |
| **TRANSMITIR_NOTA_FISCAL_AO_SALVAR** | `S` ou `N` | `S`: Exibe janela perguntando sobre transmissão. `N`: Não exibe janela. |
| **EXIGIR_PROJETO_DESPESA** | `S` | Torna obrigatório o projeto em Cotações, Pedidos, Despesas e Contas a Pagar. |
| **HABILITAR_COMPOSICAO_PRECO_PRODUTO** | `S` | Habilita composição de preço no cadastro (requer margem/preço habilitado). |
| **FRONTSELLER_ATUALIZAR_DASHBOARD_AO_INTEGRAR** | `S` ou `N` | `S`: Atualiza ao integrar pedido. `N`: Atualiza apenas no carregamento de dados. |
| **IMPORTAR_CONSUMO_AO_COPIAR_MAPA_PRODUCAO** | - | Importa consumos do mapa financeiro para o mapa fiscal. |
| **LOCAL_DESPESA_VARIAVEL_COMPOSICAO_PRECO** | `E` ou `G` | Cálculo de Despesas Variáveis: `E` (Por Empresa) ou `G` (Por Grupo de Produtos). |
| **DRE_RECEITAS_OPERACIONAIS** (e similares 1-8) | Nome Personalizado | Altera o nome dos totalizadores da DRE (Receitas, Deduções, Custos, etc.). |
| **VALIDAR_TELEFONE_UNICO_PESSOA** | `S` | Impede telefones duplicados entre Clientes, Fornecedores e Transportadoras. |
| **DIAS_LIMITE_PAGAMENTO_BOLETO** | Dias ou `0` | Define data-limite no arquivo de remessa. `0` usa o padrão do banco. |
| **EXIGIR_PROJETO_RECEITA** | `S` | Define preenchimento de projetos obrigatório em saídas. |
| **DIAS_LIMITE_CANCELAMENTO** | Dias | Limite de dias para cancelar uma venda após emissão. |
| **SUGERIR_UTILIZACAO_FIDELIDADE_CLIENTE** | - | Sugere sempre utilizar saldo de cashback disponível nas vendas. |
| **INFO_ADICIONAL_PADRAO_SN** | Texto | Define descrição padrão nos dados adicionais da DANFe (Simples Nacional). |
| **IMPRIMIR_ACERTO_CLIENTE_SIMPLES_AO_SALVAR** | `S` | Imprime automaticamente relatório de acerto ao realizar baixas simples. |
| **HABILITAR_ADIANTAMENTO_LOCACAO** | `S` | Habilita lançamento de adiantamentos em Locações. |
| **COPIAR_CODIGO_BARRAS_AUXILIAR_IMPORTAR_NOTA_FISCAL** | `S` | Copia código de barras da NF para o campo código auxiliar na importação. |
| **PERMITIR_ITEM_SERVICO_NF** | `S` | Permite inserir produtos tipo "Serviço" em NFs modelo 55. |