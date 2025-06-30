# Atividade-Modular -- Apache-spark

 <p>
    Este repositório contém a solução desenvolvida para a <strong>Atividade Modular do Módulo 3 da Pós-graduação em Engenharia de Dados</strong>
  </p>

  <p>
    O projeto utiliza <strong>Apache Spark</strong> para realizar uma análise exploratória dos dados de estabelecimentos brasileiros, abordando temas como inferência de schema, formato Parquet, limpeza de dados e extração de insights analíticos.
  </p>
<h2>🎯 Objetivos</h2>
<p>Este projeto tem como propósito exercitar, na prática, conceitos fundamentais do ecossistema de Big Data com o Apache Spark, incluindo:</p>
<ul>
  <li>📄 <strong>Spark SQL</strong> para consultas, filtragens e manipulação de grandes volumes de dados.</li>
  <li>🧩 <strong>UDFs (User Defined Functions)</strong> para tratamento e enriquecimento de dados de forma personalizada.</li>
  <li>🧱 Uso do <strong>formato Parquet</strong>, amplamente adotado para armazenamento eficiente em Data Lakes.</li>
  <li>⚙️ Aplicação de <strong>conhecimentos gerais sobre o funcionamento do Apache Spark</strong>, incluindo schema inference, transformação e análise distribuída.</li>
</ul>

<h2>📂 Conjunto de Dados</h2>
<p>
  Os arquivos de dados utilizados neste projeto estão incluídos na pasta <code>/data</code> do repositório, com os seguintes arquivos principais:
</p>
<ul>
  <li><code>estabelecimentos.csv</code> – Contém informações cadastrais dos estabelecimentos.</li>
  <li><code>cnaes.csv</code> – Lista dos CNAEs com suas descrições e códigos.</li>
</ul>
<p>
  Esses arquivos foram utilizados diretamente na análise com o Apache Spark, usando <code>inferSchema=true</code> para identificar automaticamente os tipos de dados.
</p>

 <h2>❓ Perguntas a serem respondidas</h2>
<ol>
  <li>Quantos estabelecimentos existem?</li>
  <li>Na tabela de estabelecimentos, quantas colunas existem e quantas são identificadas pelo Spark como números? Use o <code>inferSchema</code> ao ler os arquivos.</li>
  <li>Comparando o tamanho do(s) arquivo(s) CSV original(is) com o arquivo Parquet gerado pelo Spark (<code>estabelecimentos.parquet</code>), qual é a economia de espaço obtida?</li>
  <li>Quantos estabelecimentos não têm logradouro cadastrado?</li>
  <li>Quantos estabelecimentos têm um logradouro cujo endereço está incorretamente preenchido com "AVENIDA" na coluna <code>LOGRADOURO</code>?</li>
  <li>Quantos CEPs distintos existem entre os estabelecimentos?</li>
  <li>Quantos CNAEs existem na tabela de CNAEs?</li>
  <li>Quantos estabelecimentos possuem um CNAE relacionado a cultivo?</li>
  <li>Quantos estabelecimentos são filiais?</li>
</ol>
