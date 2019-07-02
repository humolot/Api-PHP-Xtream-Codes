# Api-PHP-Xtream-Codes
UTILIZANDO A API XTREAM DE FORMA SIMPLES
  
Os metodos são acessados via GET ou POST apartir do envio de aluns paramêtros
 
  Login e Senha = Obrigatorio em todas as requisições
 
  Chamada Login: 
  api.php?op=login&usuario=USUARIO&senha=SENHA
 
  Chamada Categorias de Canais:
  api.php?op=categoria_canais&usuario=USUARIO&senha=SENHA
 
  Chamada Todos os Canais:
  api.php?op=canais&usuario=USUARIO&senha=SENHA
 
  Chamada Canais por Categoria:
  api.php?op=canais&categoria=ID&usuario=USUARIO&senha=SENHA
 
  Chamada Categorias de Vods (Filmes):
  api.php?op=categoria_vods&usuario=USUARIO&senha=SENHA
 
  Camada Todos os Vods (Filmes):
  api.php?op=vods&categoria=ID&usuario=USUARIO&senha=SENHA
 
  Chamada Vods por Categoria:
  api.php?op=vods&categoria=ID&usuario=USUARIO&senha=SENHA
 
  Chamada Categorias Séries:
  api.php?op=categoria_series&usuario=USUARIO&senha=SENHA
 
  Chamada Todas as Séries:
  api.php?op=series&usuario=USUARIO&senha=SENHA
 
  Chamada Séries por Categoria:
  api.php?op=series&categoria=ID&usuario=USUARIO&senha=SENHA
 
  Chamada Informações do Vod (Filme):
  api.php?op=vod&id=ID&usuario=USUARIO&senha=SENHA
 
  Chamada Informações da Série
  api.php?op=serie&id=ID&usuario=USUARIO&senha=SENHA
 
  Camada EPG Resumido Por Canal
  api.php?op=epg_simples&id=ID&usuario=USUARIO&senha=SENHA
 
  Camada EPG Completo Por Canal
  api.php?op=epg&id=ID&usuario=USUARIO&senha=SENHA
 
  Camada Todo EPG Full
  api.php?op=epgfull&usuario=USUARIO&senha=SENHA
 
 
  Faça as chamads através do seu navegador pela URL que você ai utilizar 
  Exemplo: www.meudominio.com/api.php?op=epgfull&usuario=USUARIO&senha=SENHA
 
  Verão 1.0 
  Necessário Tratar e Adaptar Arrys e Valores
