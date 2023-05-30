# arrumar_busca_sm30
Arruma busca de SM30 customizada 
QUando customizamos uma sm30 a busca fica zoada então devemos criar um ehancement na função TABLE_GET_KEY_TO_SET_CUR_ROW e exportar a tabela sval_tab para memória e pegar a mesma no PBO em um modulo z criado, fazer a leitura do index na extract e depois de pegar o index move-lo para nextline e para tctrl_ztbfi833-top_line.
ver prints e códigos.
