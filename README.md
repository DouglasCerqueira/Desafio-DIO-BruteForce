# Desafio Bootcamp Santander/DIO - Simulando um Ataque de Brute Force de Senhas com Medusa e Kali Linux

Todo o projeto foi baseado nas seguintes configurações abaixo:
  - Oracle VirtualBox: https://www.virtualbox.org
  - Kali Linux: https://www.kali.org
  - Metasploitable 2: https://sourceforge.net/projects/metasploitable/files/Metasploitable2

Tanto o Kali Linux e o Metasploitable 2 foram configurados na virtualbox no modo de rede host-only, para conseguirem se comunicar entre si.
   - IP do Kali Linux: 192.168.56.102
   - IP do Metasploitable 2: 192.168.56.101

Para testarmos se realmente a conectividade funcionou o codigo abaixo foi utilizado:

![conexao](images/ping.png)
-c 3: Envia 3 pacotes ICMP para o IP desejado
