# Laboratório de Cybersegurança – Estudos Práticos
## Sobre o Projeto

Este repositório contém experimentos desenvolvidos para fins educacionais, com foco em compreender o funcionamento de ameaças reais e aprender técnicas de defesa em segurança da informação.

⚠️ Todos os testes foram realizados em ambiente isolado e controlado, sem qualquer finalidade maliciosa.

# 🦠 Simulação de Ransomware

## 🎯 Objetivo

Entender como funciona o processo de:

- Geração de chave criptográfica

- Criptografia de arquivos

- Criação de mensagem de resgate

- Impacto em diretórios específicos

## 🧠 Conceitos Estudados

- Criptografia simétrica (Fernet)

- Manipulação de arquivos com Python

- Percurso de diretórios com os.walk

- Impacto operacional de um ataque de ransomware

## 🔎 Funcionamento (Resumo Técnico)

- Geração de chave criptográfica

- Leitura de arquivos em diretório específico

- Criptografia dos arquivos encontrados

- Criação de mensagem simulando resgate

## 🛡️ Como se Defender

- Backups frequentes

- Controle de privilégios

- Monitoramento de alterações em massa de arquivos

- Antivírus/EDR

- Políticas de Zero Trust

# ⌨️ Simulação de Keylogger
## 🎯 Objetivo

Compreender como softwares maliciosos podem capturar entradas do teclado.

🧠 Conceitos Estudados

- Eventos de teclado

- Captura de input

- Escrita em arquivos de log

- Tratamento de teclas especiais

## 🔎 Funcionamento (Resumo Técnico)

- Listener que monitora eventos de teclado

- Registro de caracteres digitados

- Armazenamento em arquivo de log

- Tratamento de teclas especiais (enter, tab, space)

🛡️ Como se Defender

- Antivírus atualizado

- Monitoramento de processos suspeitos

- Uso de autenticação multifator

- Gerenciadores de senha

- Hardening do sistema operacional

## 📚 Habilidades Desenvolvidas

- Python aplicado à segurança ofensiva

- Entendimento de malware real

- Criptografia aplicada

- Análise de comportamento malicioso

- Mentalidade defensiva (Blue Team)

⚠️ Aviso Legal

Este projeto foi desenvolvido exclusivamente para fins educacionais e testes em ambiente controlado.
Não incentivo nem apoio o uso dessas técnicas para atividades ilegais.
