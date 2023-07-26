# PROJETO[jr]
'''
PROJETO_01 CHESK LIST GERADOR
PROGAMADOR:JORIVALDO JUNIOR
''' 
atenc = '[ATENCIOSAMENTE HOSPITAL...]'
print(f'**[NOTIFICAÇAO DO APP CHESK LIST GERADOR]****\n')

print(f''' * O PREENCHIMENTO DESTE RELATORIO, FOI EXECULTADO
 * POR UM PROFISSIONAL HABILITADO DA ELETRICA\n''')
 
print(f'              [DADOS DO COLABORADOR]\n')

nome = input('  01- Nome :')
cargo = input('  02- Funçao :')
setor = input('  03- PDT :')
diarista_plantonista = input('  04- Diarista/Plantonista :')
gestor = input('  05- Gestor(a) :')
tipo_expeçao = input('  06- TIPO DE Inspeçao :')
data = input('  07- Data Do Chesk List :')
inf = input('  08- Informaçoes e Dados Ok!\n')

print('               [RELATORIO COMPLETO]\n')
litros_diesel = input('  09- Total De Litros, Nos Tanques :')
litros_diesel = int(litros_diesel)
torneiras_passagem = input('  10- Torneiras Passagem Dos Tanques (Ok/Ko)? :')
percentual_tanque_gerador = input('  11- Percetual  Do Tanque Do Gerador :')
nivel_oleo = input('  12- Nivel De Óleo Lub. Gerador De (0 a 5) :')
troca_oleo_filtro = input('  13- Troca de Oleo e Filtro : ')
tensao_bateria = input('  14- Tensao Da Bateria Em (V) :')
tempo_operaç_gerador = input( '  15- Tempo De Operaçao Do Gerador :')
numer_partid_gerad= input('  16- Numero De Partida Do Gerador :')
amperagem_fase = input('  17- Corrente De Fase(A) :')
fase_neutro = input('  18- Tensao L/N(V) :')
fase_fase = input('  19- Tensao L/L(V) :')
coseno = input('  20- Fator De Potencia :')
potencia_kw = input('  21- Potencia Em (KW) :')
cinco_s = input('  22- 5S Do Gerador (Ok/Ko)? :')
disjuntor = input('  23- Disjuntor(Ok/Ko)? :')
anomalia_sinistro = input('  24- Anomalia/Sinistro(Sim/Nao)?:')
alarme = input('  25- Presença De Alarme(Sim/Nao):')
escada = input('  26- Escada No Local(Sim/Nao):')
cadeado = input('  27- O Gerador Esta Fechado Corretamente!\n ')
if (litros_diesel <= 1200):
	print(f'  (OBS): FAZER O PEDIDO DO DIESEL URGENTE!\n' ) 
    
elif (litros_diesel >= 1500):
	print(f'  (OBS): OS TANQUES ESTAO BEM ABASTECIDO!') 

print(f'  *RELATORIO ENVIADO COM SUCESSO!\n')   
   
print( atenc.center(55, '*'))
