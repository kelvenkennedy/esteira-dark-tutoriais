# ESTEIRA DARK — site de tutorial / portal de início

Este projeto é uma **página demonstrativa funcional** e original, inspirada no formato de guia passo a passo de `posts.curtasolucoes.com.br/entregaveis/jarvis.html`. **Não reproduz o código, as marcas nem os textos do site consultado.**

## Conteúdo entregue

- `index.html`: página única com apresentação, tutorial, configuração de IA, primeiro vídeo, problemas comuns e demonstração da área do assinante.
- `assets/styles.css`: layout responsivo em cores dark/azul/violeta.
- `assets/app.js`: navegação, abas, botões de copiar, progresso de etapas salvo localmente, perguntas expansíveis e aviso de login ainda não configurado.
- `ROADMAP-SEGURANCA.md`: como transformar a demonstração em portal comercial, sem expor o script pago.
- `INSTRUCOES-CODEX.md`: briefing para implementar login, pagamentos e acesso protegido.

## Testar agora

Abra `index.html` no navegador. Não há dependências, bibliotecas externas nem conexão necessária. As interações básicas funcionam localmente.

Opcionalmente, rode em servidor local:

```bash
cd esteira-dark-site
python -m http.server 8080
```

Acesse `http://127.0.0.1:8080`.

## Colocar no GitHub Pages

1. Crie um repositório **somente com estes arquivos públicos**.
2. Envie a pasta do site para a raiz do repositório.
3. No GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main / (root)**.
4. Publique e abra o endereço indicado na seção Pages.
5. Mantenha o script vendido, tokens, configurações privadas e links definitivos de download fora deste repositório e fora do site público.

### Antes de vender

A tela de área do aluno é um protótipo. **Ela não autentica nem autoriza usuários**. O botão abre um aviso em vez de fingir um login ativo. Leia o roadmap para conexão com sua aplicação autenticada.

## Limites do script fornecido

O script ESTEiRA DARK v2 enviado na conversa tem paths de exemplo específicos do computador original, usa endereço IP local para Ollama e tem seleção de cenas baseada em cortes aleatórios: não há alinhamento semântico confiável entre roteiro e imagem. O portal explica esses pontos sem anunciar recursos inexistentes.

## Propriedade e conteúdo

A interface deste projeto é original. O material de referência visual pertence a seu criador. O produto não concede licenças sobre cenas, filmes, música e outros materiais de terceiros; distribua somente o que tem direito de usar.