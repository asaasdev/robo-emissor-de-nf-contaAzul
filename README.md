# robo-emissor-de-nf-contaAzul-
Robo emissor de NF para ContaAzul feito em SELENIUM IDE FIREFOX

Basta colocar login e senha do ContaAzul aonde está MEU_LOGIN_CA@EMPRESA.COM e MINHASENHA e instalar os plugins como descrito abaixo.
Depois é rodar os scripts para emitir as NF's/baixar os arquivos para envio a prefeitura - qdo necessario - como explico ao fim.

Existem alguns casos em que falha a emissão, mas o script faz o alerta.
Ele deixa vc colocar para "aceitar todos os erros", aonde ao fim ele de mostra a lista de vendas que precisa de tratativa manual.
É bem raro ocorrer erro, a gente emite quase 10 mil notas mês e o script atende super bem o financeiro aqui.


Para instalar, seguir:

<b>NO FIREFOX</b>:

1. Instalar SELENIUM IDE (testado com SELENIUM IDE 2.9.1) 

->https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/


2. Instalar SELENIUM IDE: FLOW CONTROL (testado com versao 1.0.4.1-SIGNED) 
->https://addons.mozilla.org/en-US/firefox/addon/flow-control/

3. Reiniciar Firefox

4. Copiar arquivos anexo no DESKTOP.

Para rodar:
 
1. Abrir FIREFOX

2. Clicar em Ferramentas -> Selenium IDE.

3. Clicar em Arquivo->Abrir...

4. Escolher um dos 2 Scripts a ser rodado (do Desktop: emitir nfs v3.html ou baixar nfs.html). 
    Por padrão primeiro se emite e por último se baixa para enviar a prefeitura.

5. Clicar em Ações->Play entire test suit. (Ou no botão play verde com 3 trações verdes ao lado).
