# Cidades do Brasil
Lista completa de cidades do Brasil em formato JSON divididas por unidade federativa.


**Arquivo cidades.json**

Cada registro contém o nome da cidade e a latitude e longitude do centro.

Os registros estão num array de UFs. Cada registro de UF contém a sigla, o nome e um array com a lista de cidades.

```json
{
	"uf": "RR",
	"nome": "Roraima",
	"cidades": [
		{
			"nome": "Alto Alegre",
			"lat": 2.98858,
			"lon": -61.3072
		},
		{
			"nome": "Amajari",
			"lat": 3.64571,
			"lon": -61.3692
		}
	]
}
```

**Arquivo cidades-mongodb.json**

Arquivo um pouco mais simplificado, contendo apenas a lista de cidades e coordenadas, separadas por UF e prontas para serem importadas numa collection do MongoDB. É basicamente copy/paste.


Este projeto foi uma necessidade para um projeto pessoal meu. Não consegui encontrar uma lista completa com coordenadas exatas, então gerei esta de fontes diversas. Não há restrição de uso.
