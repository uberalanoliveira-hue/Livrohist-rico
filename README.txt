Como instalar o app como PWA

1. Extraia este ZIP em uma pasta.
2. Hospede os arquivos em um servidor estático ou abra com um servidor local.
   Exemplos:
   - Python: python -m http.server 8000
   - Node: npx serve
3. Abra o endereço no Chrome.
4. No menu do navegador, use "Instalar app" ou "Adicionar à tela inicial".

Ponto crítico:
PWA não funciona corretamente abrindo o arquivo HTML como file://.
Ele precisa rodar em http:// ou https:// para o service worker funcionar.
