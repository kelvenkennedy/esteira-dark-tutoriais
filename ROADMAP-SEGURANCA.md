# Roadmap — portal comercial Esteira Dark

## Ambiente atual

O repositório público serve exclusivamente ao tutorial. **Não oferece login funcional, pagamento, download protegido ou acesso à IA.**

## Arquitetura recomendada

1. **Tutorial público:** GitHub Pages com orientação clara de instalação e suporte.
2. **Portal do comprador:** backend em servidor com login seguro, recuperação de conta e permissões.
3. **Assinaturas:** checkout oficial com validação de webhooks no servidor; renovação, vencimento, estorno e cancelamento tratados.
4. **Entrega protegida:** script e instalador armazenados fora do GitHub público, com links temporários somente para contas habilitadas.
5. **Acesso à IA:** API autenticada, cotas por cliente, registro de custos, limites de requisições e serviço Ollama restrito à rede privada.
6. **Experiência de leigos:** instalador Windows validado, tutorial com imagens da versão real, diagnóstico e suporte.
7. **Conformidade:** proteção de dados, termos de uso e política de privacidade; não distribuir mídia sem licenças.

## Requisitos técnicos antes da venda

- [ ] Script executado e testado em máquina Windows limpa
- [ ] Endereços, nomes de arquivos e caminhos configuráveis
- [ ] Alinhamento de cenas testado ou limitação explicitada
- [ ] Login, pagamento e bloqueio de acesso testados
- [ ] Download autenticado com expiração de URL
- [ ] IA com cotas, proteção contra abuso e sem segredos expostos
- [ ] Direitos de músicas, imagens, vídeos e vozes comprovados
- [ ] Backups, logs e suporte operacionais

**Não habilitar pagamentos reais ou prometer recursos concluídos antes da validação de ponta a ponta.**
