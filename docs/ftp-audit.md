# Teste 01 — Auditoria de Autenticação FTP

## 1. Objetivo

Avaliar a segurança do mecanismo de autenticação do serviço FTP em um ambiente de laboratório controlado, utilizando o Kali Linux e a ferramenta Medusa.

O teste tem como finalidade compreender os riscos associados a ataques de força bruta e identificar possíveis falhas na proteção de credenciais.

## 2. Ambiente de testes

| Componente | Descrição |
|---|---|
| Sistema de auditoria | Kali Linux |
| Sistema alvo | Metasploitable 2 |
| Serviço avaliado | FTP |
| Ferramenta principal | Medusa |
| Ambiente | VirtualBox — rede isolada |

## 3. Metodologia

O teste será conduzido em ambiente virtual autorizado, utilizando uma wordlist controlada para avaliar o comportamento do mecanismo de autenticação FTP diante de tentativas automatizadas.

## 4. Execução do teste

**Status:** Aguardando execução.

Nesta seção serão registrados os comandos utilizados, parâmetros relevantes e procedimentos realizados durante a auditoria.

## 5. Evidências

As capturas de tela serão adicionadas à pasta `images/`.

- Identificação do serviço FTP.
- Execução do teste de autenticação.
- Resultado apresentado pela ferramenta.

## 6. Resultados

**Status:** Aguardando execução.

Serão registrados os resultados observados, incluindo autenticações bem-sucedidas ou falhas.

## 7. Análise técnica

A análise considerará os riscos de exposição de credenciais, ausência de mecanismos de bloqueio e possibilidade de tentativas automatizadas de autenticação.

## 8. Recomendações de segurança

- Desabilitar FTP sem criptografia e priorizar SFTP ou FTPS.
- Implementar políticas de senhas fortes.
- Limitar tentativas consecutivas de autenticação.
- Monitorar tentativas de login suspeitas.
- Restringir o acesso ao serviço por firewall.
- Utilizar mecanismos de detecção de ataques automatizados.

## 9. Conclusão

A conclusão será preenchida após a execução e análise dos resultados obtidos no laboratório.
