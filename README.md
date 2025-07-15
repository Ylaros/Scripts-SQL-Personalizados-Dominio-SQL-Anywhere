# 📊 Scripts SQL – Relatórios para Domínio (SQL Anywhere)

Este repositório contém uma coleção de **scripts SQL personalizados** desenvolvidos para uso com o **Gerador de Relatórios do sistema contábil Domínio (Thomson Reuters)**, utilizando o banco de dados **SQL Anywhere**.

Os relatórios foram criados com foco em **análises contábeis, fiscais, operacionais e de auditoria**, suprindo limitações do sistema padrão e oferecendo uma base prática para automações e extrações via ODBC/Power BI.

---

## 🎯 Objetivo

Facilitar o uso de consultas SQL no Domínio, oferecendo modelos prontos para:

- Conferência e auditoria fiscal
- Automação de processos
- Exportações para Excel
- Integrações com Power BI
- Apoio à parametrização e à análise contábil

---

## 📂 Lista de scripts disponíveis

| Script                                       | Descrição                                                                                     |
|---------------------------------------------|-----------------------------------------------------------------------------------------------|
| **1. Acumuladores Full**                    | Relação completa de todos os acumuladores de todas as empresas com seus respectivos dados.   |
| **2. Configuração de Importação - CFOP**    | Consulta prática da configuração de importação de documentos fiscais por CFOP. Ideal para revisão e exportação. |
| **3. Ficha Técnica - Notas de Entrada**     | Relatório de notas não conferidas com campos preparados para revisão e edição do analista.   |
| **4. Relação de Tabelas e Colunas**         | Mapeamento completo de todas as tabelas e colunas do banco SQL Anywhere – extremamente útil para quem desenvolve no gerador. |
| **5. Resumido com Impostos - Cupons**       | Relatório de cupons fiscais com dados essenciais e tributos destacados.                      |
| **6. Resumido com Impostos - Entradas**     | Relatório de entradas (compras) com valores de produtos, impostos e CFOP.                    |
| **7. Resumido com Impostos - Saídas**       | Relatório de notas de saída com base fiscal e tributária detalhada.                         |
| **8. Todos os Lançamentos**                 | Consulta completa de todos os lançamentos contábeis e fiscais de todas as empresas.          |

---

## ⚙️ Requisitos

- Sistema **Domínio Contábil (Thomson Reuters)** com acesso ao **Gerador de Relatórios SQL**
- Permissão de leitura no banco SQL Anywhere do Domínio
- Editor de texto para ajustes (Notepad++, VS Code, etc.)

---

## 📎 Observações

- Os arquivos estão no formato `.txt` para facilitar leitura, edição e importação.
- Recomenda-se testar os scripts em ambiente controlado antes de uso em produção.
- Nenhum dado sensível ou confidencial foi incluído nos arquivos.

---

## ✍️ Autor

**Aloyr Rezende**  
🔗 [LinkedIn](https://www.linkedin.com/in/aloyr-rezende)

---

## 🪪 Licença

Uso livre para fins educacionais e corporativos, com atribuição. Melhorias e sugestões são bem-vindas via pull request.
