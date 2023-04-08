<body>
	<h1>Projeto de protótipo de modelo de aprendizado de máquina para prever a quantidade de ouro extraído do minério</h1>
	<h2>Objetivo:</h2>
	<p>Desenvolver um protótipo de modelo de aprendizado de máquina para prever a quantidade de ouro puro extraído do minério de ouro.</p>
	<h2>Benefícios:</h2>
	<ul>
		<li>O modelo ajudará a otimizar a produção e eliminar parâmetros não rentáveis.</li>
	</ul>
	<h2>Etapas do projeto:</h2>
	<ol>
		<li>Preparação dos dados:
			<ul>
				<li>Abrir e estudar os arquivos gold_recovery_train.csv, gold_recovery_test.csv e gold_recovery_full.csv.</li>
				<li>Verificar se a quantidade retirada foi calculada corretamente para a característica rougher.output.recovery no conjunto de treinamento. Calcular a quantidade retirada e encontrar o EAM entre os cálculos e os valores das características.</li>
				<li>Analisar as características não disponíveis no conjunto de teste e identificar os parâmetros e seus tipos.</li>
				<li>Realizar o pré-processamento dos dados.</li>
			</ul>
		</li>
		<li>Análise dos dados:
			<ul>
				<li>Observar como a concentração de metais (Au, Ag, Pb) muda dependendo do estágio de purificação.</li>
				<li>Comparar as distribuições de tamanho de partícula de minério no conjunto de treinamento e no conjunto de teste.</li>
				<li>Considerar as concentrações totais de todas as substâncias em diferentes estágios e identificar valores anormais na distribuição total.</li>
			</ul>
		</li>
		<li>Construção do modelo:
			<ul>
				<li>Escrever uma função para calcular o valor final sMAPE.</li>
				<li>Treinar diferentes modelos e avaliá-los usando validação cruzada.</li>
				<li>Escolher o melhor modelo e testá-lo usando a amostra de teste.</li>
			</ul>
		</li>
	</ol>
	<h2>Recursos:</h2>
	<ul>
		<li>Documentação da biblioteca Pandas para manipulação de dados.</li>
		<li>Documentação da biblioteca Matplotlib para visualização de dados.</li>
		<li>Documentação da biblioteca Scikit-learn para aprendizado de máquina.</li>
	</ul>
</body>
</html>
