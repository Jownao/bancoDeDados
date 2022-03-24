~~~ 
group: CONTROLE_PEDIDOS		
		Funcionarios = { cod_func, nom_func, end_func, cid_func, uf_func, cpf, dat_nasc
		2000, 'JOSE DA SILVA',  'RUA A NRO 40', 'SAO PAULO',      'SP', '11111111111', '1980-01-01'
		3000, 'MARIA SOUZA',    'RUA B NRO 50', 'SAO PAULO',      'SP', '22222222222', '1979-01-01'
		4500, 'MARCOS ALBERTO', 'RUA C NRO 60', 'RIO DE JANEIRO', 'RJ', '33333333333', '1985-03-12'
		4950, 'ANA MARIA',      'RUA D NRO 70', 'VITORIA',        'ES', '44444444444', '1981-04-13'
		5002, 'JOSEFINA DA LUZ','RUA E NRO 80', 'SALVADOR',       'BA', '55555555555', '1994-06-15'
		5356, 'MARIANA SOARES', 'RUA F NRO 90', 'ARACAJU',        'SE', '66666666666', '1992-07-06'
		6789, 'JOSEFINA DA LUZ','RUA G NRO 86', 'PORTO ALEGRE',   'RS', '77777777777', '1989-08-17'
		8792, 'CARMELO LUIZ',   'RUA H NRO 55', 'JOINVILE',       'SC', '88888888888', '1976-09-18'
		}
		
		Pedidos = { cod_pedido, dat_pedido, dat_entrega, valor_total, desc_total, cod_func
		1, '2005-01-27', '2005-01-27', 1535, 100, 4950
		2, '2006-01-21', '2006-01-21', 567,    0, 3000
		3, '2006-01-12', '2006-01-12', 175,   12, 4950
		4, '2006-01-19', '2006-01-19', 1121,  20, 8792
		5, '2008-05-23', '2008-05-23', 785,    0, 2000
		6, '2011-06-18', '2011-06-18', 47,     0, 3000
		7, '2011-07-16', '2011-07-16', 148,   10, 3000
		8, '2020-08-14', '2020-08-14', 97,    17, 4500
		9, '2020-09-17', '2020-09-17', 1178,  17, 4500
		10,'2020-11-19', '2020-11-19', 2345, 120, 8792
		
		}
		
		Itens_de_pedidos = { cod_pedido, cod_prod, qtd_pedido, valor_venda, val_desc
		1, 200, 2, 1000, 70
		1, 202, 1, 535,  30
		2, 201, 1, 567,   0
		3, 203, 1, 175,  12
		4, 204, 1, 500,  10
		4, 205, 1, 500,  10
		4, 206, 1, 121,   0
		5, 206, 3, 785,   0
		6, 207, 1, 47,    0
		7, 207, 1, 100,   5
		7, 208, 1, 50,    5
		8, 201, 5, 50,    7 
		8, 202, 3, 47,   10
		9, 203, 2, 178,  10 
		9, 204, 1, 400,   2
		9, 206, 1, 100,   2 
		9, 207, 1, 500,   3
                10,204, 8, 1345, 60		
		10,205, 2, 1000, 60
		}
		
		Produtos = { cod_prod, dsc_prod, cod_forn, qtd_estoque, valor_produto, uf_producao
		200,'MONITOR LCD',        300, 25, 1000, 'RS'
		201,'VENTILADOR TURBO',   301,  2,  338, 'SP'
		202,'MOUSE PAD',	        300,125,   33, 'MG'
		203,'SMATPHONE XING LING',305, 47,  567, 'RS'
		204,'RESMA A4',           304,987,   33, 'ES'
 		205,'MOCHILA PRETA',      304, 78,  100, 'RJ'       
		206,'MESA DE PLÁSTICO',   302,  4,   84, 'MG'
		207,'CADEIRA DE PLÁSTICO',302, 58,   58, 'MG'
		208,'BALDE PARA OBRA',    303, 37,  100, 'PR'  
		
		}
		
		Fornecedores = { cod_forn, nom_forn, uf_forn
		300, 'CASA DA TI', 'RS' 
		301, 'O ELETRICÃO', 'SP'
		302, 'ESCRITÓRIO E CIA', 'MG'
		303, 'O BALATÃO', 'RS'
		304, 'O PAPELÃO', 'ES'
		305, 'USINA DA OBRA', 'PR'
		}
