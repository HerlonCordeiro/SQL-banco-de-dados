# SQL-banco-de-dados
Criação de Dados

Realizei a criação de um banco de dados onde coloquei algumas querys inicial.
CREATE TABLE [dbo].[produtos](
	[codigo] [int] IDENTITY(1,1) NOT NULL,
	[nome_produto] [varchar](20) NOT NULL,
	[quantidade] [int] NOT NULL,
	[valor] [decimal](10, 2) NULL,
PRIMARY KEY CLUSTERED 
)
