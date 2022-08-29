# API

As APIs são um conjunto de padrões que fazem parte de uma interface e que permitem a criação de plataformas de maneira mais simples e prática para desenvolvedores. A partir de APIs é possível criar softwares, **aplicativos**, programas e plataformas diversas. Por exemplo, apps desenvolvidos para celulares **Android** e **iPhone** (**iOS**) são criados a partir de padrões definidos e disponibilizados pelas APIs de cada sistema operacional.

<p align="center">
  <img width="460" height="300" src="https://suppay.com.br/wp-content/uploads/2021/05/mad_blog_5db041379523b1571832119.gif">
</p>

------

## O que significa API?

A sigla API deriva da expressão inglesa *Application Programming Interface* que, traduzida para o português, pode ser compreendida como uma interface de programação de aplicação. Ou seja, API é um conjunto de normas que possibilita a comunicação entre plataformas através de uma série de padrões e protocolos. Por meio de APIs, desenvolvedores podem criar novos softwares e aplicativos capazes de se comunicar com outras plataformas. Por exemplo: caso um desenvolvedor queira criar um aplicativo de fotos para Android, ele poderá ter acesso à câmera do celular através da API do sistema operacional, sem ter a necessidade de criar uma nova interface de câmera do zero. O mesmo acontece com aplicativos que utilizam os serviços de mapas por meio da API do **Google Maps** ou, ainda, nas integrações entre apps, como o **Spotify** e o **Instagram**, que **possibilita compartilhar faixas nos Stories**.

------

## **Qual a função de uma API?**

A função de uma API é, basicamente, facilitar e simplificar o trabalho de desenvolvedores, além de oferecer um padrão para a criação de novas plataformas. Com o uso das APIs, não é necessário criar códigos personalizados para cada função que um programa for executar, o que simplifica a criação de novos aplicativos, softwares e plataformas em geral. Além disso, as APIs também possuem papel fundamental quando o assunto é segurança, já que também são capazes de bloquear acesso e permissões a dados de software e hardware que algumas aplicações não podem usar.

------

## **Exemplos de uma API**

As APIs estão presentes na maioria dos aplicativos que utilizamos no nosso dia a dia. No **WhatsApp**, por exemplo, podemos perceber a integração da lista de contatos salva no dispositivo com os contatos do aplicativo. No **Facebook**, temos a integração com o Instagram, que **permite que fotos postadas no aplicativo também sejam postadas automaticamente no Facebook**. 

Também podemos observar o uso das APIs quando realizamos compras online, já que a plataforma utilizada para pagamentos — em que colocamos as informações de cartões de crédito — deve ser integrada à operadora do cartão, que pode ou não autorizar a compra. Esses são alguns exemplos de APIs mais comuns, que podemos perceber no nosso cotidiano, e que facilitam a comunicação entre plataformas.

<p align="center">
  <img width="460" height="300" src="https://developer.spotify.com/assets/WebAPI_intro.png">
</p>



```
API viaCep retorno JSON
{
      "cep": "01001-000",
      "logradouro": "Praça da Sé",
      "complemento": "lado ímpar",
      "bairro": "Sé",
      "localidade": "São Paulo",
      "uf": "SP",
      "ibge": "3550308",
      "gia": "1004",
      "ddd": "11",
      "siafi": "7107"
    }
       
```

<p align="center">
  <img width="460" height="300" src="https://spiralking.com/wp-content/uploads/2020/04/twitter-api.jpg">
</p>

------

## **O que é uma API no mercado financeiro?**

As APIs também podem ser utilizadas para a comunicação entre serviços e, no mercado financeiro, elas funcionam através do sistema de Open Banking. A solução de Open Banking é simples e promete mudar o sistema financeiro, já que as informações de consumidores estariam disponíveis em uma base de dados padronizada capaz de se comunicar com outras instituições, o que seria possível através de APIs. Com o Open Banking, seria mais fácil realizar a portabilidade de dados de um cliente que deseja migrar para outro banco, por exemplo.

<p align="center">
  <img width="460" height="300" src="https://miro.medium.com/max/1400/1*zdaj_q66kjXS8rygZ7hOEw.gif">
</p>

------

## **Segurança na API**

A criptografia é necessária para manter os dados das APIs seguros. Por este motivo, alguns certificados precisam ser validados corretamente, sem que haja margem para criação de possíveis brechas no sistema.Quando estes certificados não são validados corretamente, essas vulnerabilidades no sistema podem ser exploradas, permitindo que hackers sejam capazes de interceptar dados de usuários, o que é potencialmente perigoso quando tratamos de informações financeiras, como o sistema de Open Banking e de dados médicos.

<p align="center">
  <img width="460" height="300"src="data:image/png;base64,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">
</p>

------

## **O que significa consumir uma API?**

Significa usá-la, ou seja, significa que seu código vai acessar a API de alguma forma. Invocará as ações disponíveis para requisitar informações, mandar realizar operações. Basta escrever um código que faça uma requisição nela, e você já está consumindo a API. Não importa o tipo de API.

<p align="center">
  <img src="https://www.sherpadesk.com/hubfs/Blog%20Images/API-Limits/Hero-API-Limits.gif">
</p>

## **Vamos consumir uma API na prática somente com JavaScript?**

