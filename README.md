# Netpractice Basics README

## Endereçamento IP

### IPv4 (Internet Protocol version 4)

O IPv4 é a versão mais amplamente utilizada do protocolo IP. Cada endereço IPv4 é um número de 32 bits dividido em quatro octetos. Cada octeto é representado em notação decimal e pode variar de 0 a 255. Por exemplo, o endereço "192.168.0.1" é um endereço IPv4 com quatro octetos.

### IPv6 (Internet Protocol version 6)

O IPv6 foi desenvolvido para superar a escassez de endereços do IPv4. Cada endereço IPv6 é composto por 128 bits, divididos em oito grupos de 16 bits cada. Cada grupo é representado em notação hexadecimal. Por exemplo, "2001:0db8:85a3:0000:0000:8a2e:0370:7334" é um endereço IPv6.

## Lógica Matemática

Para entender endereçamento IP, é crucial compreender a representação binária (base 2) e a conversão para decimal (base 10) ou hexadecimal (base 16). Isso ajuda a entender a estrutura dos endereços IP, seja em IPv4 ou IPv6.

## TCP/IP

O TCP/IP é um conjunto de protocolos de comunicação que forma a base da Internet e muitas redes. É composto por várias camadas, incluindo aplicação, transporte, rede e enlace de dados. O TCP (Transmission Control Protocol) e o IP (Internet Protocol) são os principais protocolos usados no TCP/IP.

## Divisão em Octetos

A divisão em octetos é um conceito fundamental para a representação de endereços IP. Em IPv4, um endereço é dividido em quatro octetos, cada um representado em notação decimal. Em IPv6, cada grupo de 16 bits é representado por quatro dígitos hexadecimais.

# Endereços IP Privados

## O que são Endereços IP Privados?

Os endereços IP privados são uma faixa de endereços reservada para uso em redes privadas. Eles não são roteáveis na Internet pública e são usados dentro de redes locais (LANs) e organizações. O uso desses endereços permite a comunicação interna de dispositivos em uma rede, sem a necessidade de utilizar um grande número de endereços IP públicos.

Existem três faixas de endereços IP privados definidas pela RFC 1918:

1. **Classe A Privada (10.0.0.0 a 10.255.255.255)**:
   - Ampla faixa de endereços, frequentemente usada em redes corporativas.

2. **Classe B Privada (172.16.0.0 a 172.31.255.255)**:
   - Faixa intermediária, comumente usada em empresas de médio porte.

3. **Classe C Privada (192.168.0.0 a 192.168.255.255)**:
   - Amplamente utilizada em redes domésticas e pequenas empresas.

## Importância dos Endereços IP Privados

- **Isolamento**: Permitem a comunicação interna dentro da rede, isolando-a da Internet pública, proporcionando uma camada adicional de segurança.

- **Reutilização**: Por serem reservados para uso privado, podem ser reutilizados em diferentes redes locais, sem causar conflitos de endereço.

- **Economia de Endereços Públicos**: Permitem que várias máquinas compartilhem um único endereço IP público, otimizando o uso dos endereços IP públicos, que são limitados e caros.

- **Network Address Translation (NAT)**: Técnica usada para traduzir endereços IP privados em um único endereço IP público quando os dados saem da rede privada em direção à Internet.

## Utilização Prática

Para configurar uma rede utilizando endereços IP privados, é essencial configurar o roteador para utilizar NAT. Isso permitirá a tradução de endereços privados em um único endereço público, facilitando a comunicação com a Internet.

Na configuração dos dispositivos, é importante utilizar endereços IP dentro das faixas reservadas para uso privado, garantindo o funcionamento adequado da rede local.

