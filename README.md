<p align="center">
  <img src="assets/acerto-miseravi.png" width="100" />
  <h2 align="center">Front-end Challenge</h2>
</p>

---

A NOALVO é a maior plataforma brasileira de planejamento e compra de mídia out-of-home (ex: Relógio de rua, Outdoor..) e lidamos bastante com calculos de trigonometria e coisas relacionadas a latitude e longitude, então como você já deve imaginar, o nosso maior desafio no Front é justamente lidar com mapas e manter a UI leve e usável em qualquer dispositivo.

O teste é basicamente o seguinte, use a API do [Google Maps](https://developers.google.com/maps/documentation/javascript/tutorial) para plotar os dados do JSON que vem desse [endpoint]().

o JSON segue essa estrutura:

```json
{
  "markers": [
    [-34.397, 150.644], // Lat e Lng respectivamente
    [-32.397, 120.644], // Lat e Lng respectivamente
  ],
  "audiencia": [
    
  ]
}
```

### Sobre a entrega do teste

Responda o email que nós já estavamos conversando com o link do seu repositório que você colocou o código

#### OBS

+ *Você não precisa terminar todo o desafio, nós avaliaremos seu código e a sua intenção em fazer as coisas, quando achar que esta pronto envie o projeto!*
+ No README do projeto precisa ter como rodar ele.

### Sobre o Framework

Aqui usamos [Vue.js](http://vuejs.org), mas fique a vontade para usar React, só tenha em mente que aqui as coisas serão implementadas em Vue :D