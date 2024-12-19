FROM ubuntu
RUN apt update && apt install -y curl
LABEL contato="jmarcelotse@hotmail.com"
LABEL versao="0.1"
WORKDIR /app
ADD https://www.google.com.br/favicon.ico pagina.html
ADD teste.tar.gz ./
CMD ["cat", "pagina.html"]