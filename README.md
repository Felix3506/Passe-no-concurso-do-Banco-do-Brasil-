# Passe-no-concurso-do-Banco-do-Brasil-
Passe para o Banco do Brasil 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apostila Banco do Brasil</title>
    <style>
        :root {
            --portuguese: #FF6B6B;
            --math: #4ECDC4;
            --logic: #45B7D1;
            --banking: #F9A826;
            --consumer: #A3D39C;
            --english: #9B59B6;
            --dark: #2C3E50;
            --light: #ECF0F1;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 25px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        header {
            background: linear-gradient(135deg, #0033A0 0%, #0038A8 100%);
            color: white;
            padding: 30px 0;
            text-align: center;
            margin-bottom: 30px;
        }
        
        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .logo-circle {
            width: 100px;
            height: 100px;
            background-color: #FEDD00;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-weight: bold;
            font-size: 24px;
            color: #0033A0;
            border: 4px solid white;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .controls {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
            background: var(--light);
            margin-bottom: 20px;
        }
        
        .btn {
            padding: 12px 25px;
            border: none;
            border-radius: 50px;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .btn-primary {
            background: var(--banking);
            color: white;
        }
        
        .btn-primary:hover {
            background: #e59700;
            transform: translateY(-2px);
        }
        
        .btn-secondary {
            background: var(--dark);
            color: white;
        }
        
        .btn-secondary:hover {
            background: #1a252f;
            transform: translateY(-2px);
        }
        
        #apostila {
            padding: 20px;
        }
        
        .subjects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }
        
        .subject-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
        }
        
        .subject-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
        }
        
        .subject-header {
            padding: 20px;
            color: white;
            text-align: center;
        }
        
        .subject-body {
            padding: 20px;
        }
        
        .subject-body h3 {
            margin-bottom: 15px;
            font-size: 1.4rem;
        }
        
        .subject-body ul {
            list-style-type: none;
        }
        
        .subject-body li {
            padding: 8px 0;
            border-bottom: 1px dashed #eee;
            display: flex;
            align-items: center;
        }
        
        .subject-body li:before {
            content: "•";
            margin-right: 10px;
            font-size: 1.5rem;
        }
        
        .portuguese { background-color: var(--portuguese); }
        .math { background-color: var(--math); }
        .logic { background-color: var(--logic); }
        .banking { background-color: var(--banking); }
        .consumer { background-color: var(--consumer); }
        .english { background-color: var(--english); }
        
        .content-section {
            background: white;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
        }
        
        .content-header {
            display: flex;
            align-items: center;
            margin-bottom: 25px;
            padding-bottom: 15px;
            border-bottom: 2px solid;
        }
        
        .content-icon {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-right: 15px;
            color: white;
            font-size: 1.5rem;
        }
        
        .content-body h3 {
            margin: 20px 0 10px;
            color: var(--dark);
        }
        
        .content-body p {
            margin-bottom: 15px;
            text-align: justify;
        }
        
        .tip-box {
            background-color: #f8f9fa;
            border-left: 4px solid;
            padding: 15px;
            margin: 20px 0;
            border-radius: 0 8px 8px 0;
        }
        
        .example-box {
            background-color: #f0f7ff;
            border: 1px solid #d0e3ff;
            padding: 15px;
            margin: 20px 0;
            border-radius: 8px;
        }
        
        .key-points {
            background-color: #fff4e6;
            padding: 20px;
            border-radius: 8px;
            margin: 20px 0;
        }
        
        .key-points h4 {
            margin-bottom: 10px;
            color: #e67700;
        }
        
        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 40px;
            background-color: var(--dark);
            color: white;
        }
        
        @media (max-width: 768px) {
            .subjects-grid {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .controls {
                flex-direction: column;
                align-items: center;
            }
            
            .btn {
                width: 100%;
                justify-content: center;
            }
        }
        
        /* Estilos para impressão */
        @media print {
            .controls {
                display: none;
            }
            
            body {
                padding: 0;
                background: white;
            }
            
            .container {
                box-shadow: none;
                border-radius: 0;
            }
            
            .subject-card {
                break-inside: avoid;
            }
            
            .content-section {
                break-inside: avoid;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <div class="logo-circle">BB</div>
            </div>
            <h1>Concurso Banco do Brasil</h1>
            <p class="subtitle">Apostila Completa e Didática para sua Preparação</p>
        </header>
        
        <div class="controls">
            <button class="btn btn-primary" onclick="window.print()">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                    <path d="M5 1a2 2 0 0 0-2 2v1h10V3a2 2 0 0 0-2-2H5zm6 8H5a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1z"/>
                    <path d="M0 7a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-1v-2a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v2H2a2 2 0 0 1-2-2V7zm2.5 1a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1z"/>
                </svg>
                Imprimir
            </button>
        </div>
        
        <div id="apostila">
            <div class="subjects-grid">
                <div class="subject-card">
                    <div class="subject-header portuguese">
                        <h2>Língua Portuguesa</h2>
                    </div>
                    <div class="subject-body">
                        <h3>Conteúdo Abordado</h3>
                        <ul>
                            <li>Interpretação de Texto</li>
                            <li>Gramática e Ortografia</li>
                            <li>Pontuação</li>
                            <li>Coesão e Coerência</li>
                            <li>Redação Oficial</li>
                            <li>Exercícios Comentados</li>
                        </ul>
                    </div>
                </div>
                
                <div class="subject-card">
                    <div class="subject-header math">
                        <h2>Matemática</h2>
                    </div>
                    <div class="subject-body">
                        <h3>Conteúdo Abordado</h3>
                        <ul>
                            <li>Números Inteiros e Racionais</li>
                            <li>Sistema de Medidas</li>
                            <li>Equações e Inequações</li>
                            <li>Porcentagem e Juros</li>
                            <li>Análise Combinatória</li>
                            <li>Estatística Básica</li>
                        </ul>
                    </div>
                </div>
                
                <div class="subject-card">
                    <div class="subject-header logic">
                        <h2>Raciocínio Lógico-Matemático</h2>
                    </div>
                    <div class="subject-body">
                        <h3>Conteúdo Abordado</h3>
                        <ul>
                            <li>Estruturas Lógicas</li>
                            <li>Lógica de Argumentação</li>
                            <li>Diagramas Lógicos</li>
                            <li>Sequências e Padrões</li>
                            <li>Proposições e Tabelas-Verdade</li>
                            <li>Problemas Lógicos Diversos</li>
                        </ul>
                    </div>
                </div>
                
                <div class="subject-card">
                    <div class="subject-header banking">
                        <h2>Direitos Bancários</h2>
                    </div>
                    <div class="subject-body">
                        <h3>Conteúdo Abordado</h3>
                        <ul>
                            <li>Sistema Financeiro Nacional</li>
                            <li>Produtos e Serviços Financeiros</li>
                            <li>Ética e Segurança</li>
                            <li>Normas do BACEN</li>
                            <li>Siglas do Mercado Financeiro</li>
                            <li>Atendimento ao Cliente</li>
                        </ul>
                    </div>
                </div>
                
                <div class="subject-card">
                    <div class="subject-header consumer">
                        <h2>Código de Defesa do Consumidor</h2>
                    </div>
                    <div class="subject-body">
                        <h3>Conteúdo Abordado</h3>
                        <ul>
                            <li>Princípios e Direitos Básicos</li>
                            <li>Práticas Comerciais</li>
                            <li>Proteção Contratual</li>
                            <li>Sanções Administrativas</li>
                            <li>Direitos na Relação Bancária</li>
                            <li>Jurisprudência Aplicada</li>
                        </ul>
                    </div>
                </div>
                
                <div class="subject-card">
                    <div class="subject-header english">
                        <h2>Língua Inglesa</h2>
                    </div>
                    <div class="subject-body">
                        <h3>Conteúdo Abordado</h3>
                        <ul>
                            <li>Interpretação de Textos</li>
                            <li>Vocabulário Bancário</li>
                            <li>Gramática Aplicada</li>
                            <li>Termos Técnicos</li>
                            <li>Exercícios de Compreensão</li>
                            <li>Dicas para Provas</li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div class="content-section">
                <div class="content-header portuguese">
                    <div class="content-icon portuguese">P</div>
                    <h2>Língua Portuguesa</h2>
                </div>
                <div class="content-body">
                    <h3>Interpretação de Texto</h3>
                    <p>A interpretação de texto é fundamental para qualquer prova de concurso. É através dela que se compreende o enunciado das questões e se identifica a intenção do autor.</p>
                    
                    <div class="tip-box" style="border-left-color: var(--portuguese);">
                        <strong>Dica:</strong> Leia o texto至少 duas vezes. Na primeira, faça uma leitura geral para entender o contexto. Na segunda, leia com mais atenção para capturar detalhes importantes.
                    </div>
                    
                    <h3>Pontuação</h3>
                    <p>A pontuação adequada é essencial para a clareza do texto. Vírgulas, pontos, dois-pontos e ponto e vírgula têm funções específicas que alteram o sentido das frases.</p>
                    
                    <div class="example-box">
                        <strong>Exemplo:</strong> "Vamos perder, não há tempo" versus "Vamos perder não, há tempo". A simples mudança da vírgula altera completamente o sentido da frase.
                    </div>

                    <h3>Coesão e Coerência</h3>
                    <p>Coesão refere-se aos elementos formais que conectam as partes do texto, enquanto coerência diz respeito ao sentido, à lógica do texto.</p>
                    
                    <div class="key-points">
                        <h4>Elementos de Coesão:</h4>
                        <p>• Pronomes (eles, isso, aquilo)</p>
                        <p>• Conjunções (e, mas, portanto)</p>
                        <p>• Advérbios (aqui, então, assim)</p>
                        <p>• Sinônimos e repetições estratégicas</p>
                    </div>
                </div>
            </div>
            
            <div class="content-section">
                <div class="content-header math">
                    <div class="content-icon math">M</div>
                    <h2>Matemática</h2>
                </div>
                <div class="content-body">
                    <h3>Porcentagem e Juros</h3>
                    <p>Os cálculos de porcentagem são frequentes em provas de concursos bancários. É importante dominar tanto o cálculo simples de porcentagem quanto os juros simples e compostos.</p>
                    
                    <div class="key-points">
                        <h4>Fórmulas Importantes:</h4>
                        <p>Juros Simples: J = C × i × t</p>
                        <p>Juros Compostos: M = C × (1 + i)^t</p>
                        <p>Onde: J = juros, C = capital, i = taxa, t = tempo, M = montante</p>
                    </div>
                    
                    <h3>Análise Combinatória</h3>
                    <p>Esta área da matemática estuda as possibilidades de combinação de elementos. É dividida principalmente em arranjos, combinações e permutações.</p>
                    
                    <div class="tip-box" style="border-left-color: var(--math);">
                        <strong>Dica:</strong> Use o princípio fundamental da contagem: se um evento pode ocorrer de m maneiras e outro de n maneiras, então os dois juntos podem ocorrer de m × n maneiras.
                    </div>
                    
                    <h3>Estatística Básica</h3>
                    <p>Conceitos como média, mediana, moda e desvio padrão são frequentemente cobrados. A média é a soma de todos os valores dividida pela quantidade de valores.</p>
                    
                    <div class="example-box">
                        <strong>Exemplo:</strong> Calcule a média de 4, 6, 8 e 10: (4+6+8+10)/4 = 28/4 = 7.
                    </div>
                </div>
            </div>
            
            <div class="content-section">
                <div class="content-header logic">
                    <div class="content-icon logic">L</div>
                    <h2>Raciocínio Lógico-Matemático</h2>
                </div>
                <div class="content-body">
                    <h3>Lógica de Argumentação</h3>
                    <p>A lógica de argumentação analisa a validade dos argumentos. Um argumento é válido quando a conclusão é uma consequência necessária das premissas.</p>
                    
                    <div class="example-box">
                        <strong>Exemplo:</strong> Premissa: Todos os mamíferos têm pulmões. Premissa: Baleias são mamíferos. Conclusão: Baleias têm pulmões. Este é um argumento válido.
                    </div>
                    
                    <h3>Diagramas Lógicos</h3>
                    <p>Os diagramas lógicos, especialmente os diagramas de Venn, são úteis para resolver problemas que envolvem conjuntos e relações entre eles.</p>
                    
                    <div class="tip-box" style="border-left-color: var(--logic);">
                        <strong>Dica:</strong> Comece sempre pela informação que relaciona mais conjuntos ao resolver problemas com diagramas de Venn.
                    </div>
                    
                    <h3>Sequências e Padrões</h3>
                    <p>Sequências podem ser numéricas, alfabéticas ou figurativas. O importante é identificar o padrão que rege a sequência.</p>
                    
                    <div class="example-box">
                        <strong>Exemplo:</strong> Qual o próximo número na sequência: 2, 4, 8, 16, ___? Resposta: 32 (cada termo é o dobro do anterior).
                    </div>
                </div>
            </div>
            
            <div class="content-section">
                <div class="content-header banking">
                    <div class="content-icon banking">B</div>
                    <h2>Direitos Bancários</h2>
                </div>
                <div class="content-body">
                    <h3>Sistema Financeiro Nacional</h3>
                    <p>O SFN é composto por entidades normativas, supervisoras e operadoras. O Banco Central do Brasil (BACEN) é a principal instituição supervisoras do sistema.</p>
                    
                    <div class="tip-box" style="border-left-color: var(--banking);">
                        <strong>Importante:</strong> Memorize as principais siglas: CMN (Conselho Monetário Nacional), BACEN (Banco Central do Brasil), CVM (Comissão de Valores Mobiliários).
                    </div>
                    
                    <h3>Produtos e Serviços Financeiros</h3>
                    <p>Os bancos oferecem diversos produtos, desde conta corrente até investimentos. É importante conhecer as características de cada um e suas taxas.</p>
                    
                    <div class="key-points">
                        <h4>Principais Produtos Bancários:</h4>
                        <p>• Conta corrente e poupança</p>
                        <p>• Empréstimos pessoais e consignados</p>
                        <p>• Financiamentos imobiliários e veículos</p>
                        <p>• Cartões de crédito e débito</p>
                        <p>• Investimentos: CDB, LCI, LCA, Tesouro Direto</p>
                    </div>
                    
                    <h3>Ética e Segurança</h3>
                    <p>O código de ética bancária estabelece padrões de conduta para os funcionários. A segurança das transações e a proteção de dados são prioridades.</p>
                </div>
            </div>
            
            <div class="content-section">
                <div class="content-header consumer">
                    <div class="content-icon consumer">C</div>
                    <h2>Código de Defesa do Consumidor</h2>
                </div>
                <div class="content-body">
                    <h3>Princípios e Direitos Básicos</h3>
                    <p>O CDC estabelece direitos e obrigações para consumidores e fornecedores. Entre os princípios estão a vulnerabilidade do consumidor e a boa-fé objetiva.</p>
                    
                    <div class="example-box">
                        <strong>Exemplo de direito:</strong> O artigo 6º do CDC estabelece como direito básico do consumidor a proteção contra publicidade enganosa e abusiva.
                    </div>
                    
                    <h3>Práticas Comerciais</h3>
                    <p>O código proíbe práticas abusivas, como a venda casada e a cobrança de dívidas não reconhecidas. Também regula a publicidade e as ofertas.</p>
                    
                    <div class="tip-box" style="border-left-color: var(--consumer);">
                        <strong>Importante:</strong> O CDC considera prática abusiva a cobrança de dívidas já prescritas. O prazo prescricional é de 5 anos.
                    </div>
                    
                    <h3>Direitos na Relação Bancária</h3>
                    <p>As relações entre bancos e clientes são regidas pelo CDC. O cliente tem direito a informações claras sobre tarifas, juros e demais encargos.</p>
                    
                    <div class="key-points">
                        <h4>Direitos do Consumidor Bancário:</h4>
                        <p>• Contratação de serviços de forma clara e transparente</p>
                        <p>• Revisão de contratos com cláusulas abusivas</p>
                        <p>• Cobrança de tarifas apenas pelos serviços efetivamente utilizados</p>
                        <p>• Restrição ao uso de dados pessoais</p>
                    </div>
                </div>
            </div>
            
            <div class="content-section">
                <div class="content-header english">
                    <div class="content-icon english">E</div>
                    <h2>Língua Inglesa</h2>
                </div>
                <div class="content-body">
                    <h3>Interpretação de Textos</h3>
                    <p>As provas de inglês para concursos bancários geralmente focam em interpretação de textos, com vocabulário relacionado ao mundo financeiro e empresarial.</p>
                    
                    <div class="tip-box" style="border-left-color: var(--english);">
                        <strong>Dica:</strong> Não é necessário entender todas as palavras do texto. Foque nas palavras-chave e no contexto para deduzir o significado.
                    </div>
                    
                    <h3>Vocabulário Bancário</h3>
                    <p>Algumas palavras importantes: loan (empréstimo), interest rate (taxa de juros), mortgage (hipoteca), withdrawal (saque), deposit (depósito), wire transfer (transferência eletrônica).</p>
                    
                    <div class="key-points">
                        <h4>Expressões Comuns em Textos Bancários:</h4>
                        <p>• "Overdraft" - limite adicional na conta</p>
                        <p>• "Statement" - extrato bancário</p>
                        <p>• "Balance" - saldo</p>
                        <p>• "Due date" - data de vencimento</p>
                        <p>• "Credit score" - pontuação de crédito</p>
                    </div>
                    
                    <h3>Estratégias de Leitura</h3>
                    <p>Skimming (leitura rápida para ter uma ideia geral) e scanning (busca por informações específicas) são técnicas úteis para provas de concurso.</p>
                    
                    <div class="example-box">
                        <strong>Exemplo:</strong> Antes de ler o texto detalhadamente, faça uma leitura rápida para identificar sua estrutura e ideia principal.
                    </div>
                </div>
            </div>
        </div>
        
        <footer>
            <p>© 2023 Apostila para Concurso Banco do Brasil - Todos os direitos reservados</p>
            <p>Material didático para fins educacionais</p>
        </footer>
    </div>
</body>
</html>
