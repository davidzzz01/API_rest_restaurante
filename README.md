para conseguir acessar os dados bastante fazer a requisição no servidor local atraves da URL:


http://localhost/api_restaurante/api/clientes.php | 
http://localhost/api_restaurante/api/cardapio.php| 
http://localhost/api_restaurante/api/pedidos.php | 
http://localhost/api_restaurante/api/categoria.php |

sem esquecer de passar os cabeçalhos na requisição:
 headers: { 'Content-Type': 'application/json'}
