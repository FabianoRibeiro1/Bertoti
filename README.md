# Bertoti
1 - Comentário do livro Software Engineering at google parte 1.

Na primeira parte do livro o escritor faz alguns questionamentos acerca do significado de engenharia de software e ciência da computação,
e diz que os termos tem sido usados ao mesmo tempo na indústria porém cada um tem ênfase e implicações diferentes.
Segundo o trecho, estudantes de ciência da computação tendem a procurar empregos escrevendo códigos como programadores (o que também podemos ver bastante por aqui) enquanto engenharia de software soa mais "sério" e implica um conhecimento teórico e técnico para criar algo mais real e preciso. O que diferencia estes de por exemplo engenharias mais comuns como mecânica, elétrica entre outras é que estes profissionais criam coisas mais "físicas, palpáveis" enquanto engenheiros de software criam algo um pouco menos tangível.
Outra diferença importante na minha opinião é a sensação de que engenheiros de software tem menos regras a seguir ou seus erros podem ser mais "toleráveis ou aceitáveis" comparados a um engenheiro aeronáutico por exemplo onde um erro pode causar muitas mortes, poré pode não ser na mesma proporção mas a responsabilidade também é muito grande e tende aumentar cada vez mais com o passar dos anos.

2 - Comentário do livro Software Engineering at google parte 2.

Na segunda parte do livro o autor questiona e no faz pensar sobre como podemos descobrir e aplicar maneiras mais sustentáveis, rigorosas e eficazes de se aprimorar a profissão, o que segundo ele próprio ainda não se tem uma resposta fundamental mas espera que todo esse tempo e esse caminho trilhado tenha iluminado mentes ao redor do mundo á procura de um caminho para isso, aliás o compartilhamento desse livro por sí só já é um ótimo caminho pois nos faz pensar e discutir sobre o tema incluindo os três princípios fundamentais citados pelo autor e encontrar as respostas pode ser um ótimo caminho para essa transformação.

3 - 3 exemplos de trade offs

a) Desempenho x Consumo de energia: 
Aumentar o desempenho de um dispositivo (como um computador por exemplo) pode resultar em maior consumo de energia e reduzir o consumo de energia pode significar menor desempenho. O ideal é avaliar cada caso, cada projeto e pesar os dois lados da balança para encontrar a melhor solução.

b) Privacidade x Conectividade:
Nossa vida tende a ser cada vez mais automatizada e isso é um caminho sem volta, os benefícios são inúmeros tendo em vista que nossa vida é cada vez mais corrida, porém isso também nos traz uma exposição cada vez maior. Dosar e investir em segurança pode ser um ótimo caminho.

c) Velocidade x Precisão:
Como dito anteriormente nossa vida está cada vez mais acelerada e isso é um movimento global ou seja seus clientes, sua empresa, todos a sua volta vão querer sempre agilidade e pressa em suas entregas. Nesse caso dialogo pode ser o melhor caminho, uma vez explicando que a pressa pode comprometer a qualidade todos estarão de acordo que é melhor usar o bom senso ao escolher datas e prazos, afinal todos 
 estão em busca do melhor resultado.


4 - ![alt text](<Classe UML-1.jpeg>)


5 - Mercado.java 

package mercado;

import java.util.list;
import util.LinkedList;

public class mercado {
	
	private List<Produto> produtos = new LinkedList<Produto>();
	
	public void addProduto(Produto produto) {
		produtos.add(produto);
	}
    
	public List<Produto> buscarProdutoNome(String produto){
		List<Produto> encontrados = new LinkedList<Produto>();
		  if(aluno.getProduto().equals(produto)) encontrados.add(produto);
	}
	return encontrados;
}


Teste.java

package mercado;

import static org.junit.jupter.api.Test;


import util.List;

class Teste {
	
	@test
	void test() {
		
		Mercado = new Mercado();
		mercado.addProduto(new Mercado("arroz" , "123"));
		
		assertEquals(sala.getProdutos().Size(), 1);
		
		List<Produto> produtosencontrados = mercado.buscarProduto("arroz");
		
		assertEquals(produtosencontrados.get(0).getcod(), "123");
	}
		
		
}


Produto.java

package mercado;

public class Produto {
   private String tipo;
   private String cod;


public String gettipo() {
   return tipo;
}
public void setTipo(String tipo) {
   this.tipo = tipo;
}
public String getCod() {
   return cod;
}
public void setCod(String cod) {
   this.cod = cod;
}


