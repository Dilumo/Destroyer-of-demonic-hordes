# Destroyer of demonic hordes



# Introdução

  Esse jogo pertence a uma seria de jogos de uma página, que tem como objetivo render mais conhecimento basico a mim e facilitar a entrada/volta de pessoas com menos tempo ou interesse para jogos mais complexos.
<!-- /MarkdownTOC -->
# Indice

  - [Documentação](#documentação)
      - [Highconcept](#highconcept)
      - [Enredo](#enredo)
      - [Gameplay](#gameplay)
          - [Regras](#Regras) 
          - [Elementos](#elementos) 


<!-- /MarkdownTOC -->

---

<a name="documentação"></a>
# Documentação

<a name="highconcept"></a>
##  Highconcept
  Um jogo de tabuleiro onde você tem que derotar uma horda de dêmonios para salvar a cidade de Garnelia.       
<a name="enredo"></a>                      
## Enredo
A grande cidade Garnelia em seus últimos suspiros de desespero, pede a você, nosso herói mágico para se livrar da grande horda de demônios que agora marcha em direção à cidade.
Então cabe a você acabar com esse perigo, mas lembre-se, você não sabe como lançar feitiços a distância, então infelizmente você terá que se teletransportar para o meio da horda, mas não se preocupe, este feitiço é fraco, não dura mais que alguns segundos e então você voltara para o ponto de lançamento, apenas lembre de evitar de se teletransportar em lugares vazios, isso pode fazer você ficar lá um pouco mais de tempo, e como você sabe, os demônios não gostão muito de você. Vai mago! No pior dos casos você morre!

<a name="gameplay"></a>
## Gameplay 
Com o auxilio de *dois dados* o jogador rodara o primeiro dado para **linha** e o sengundo para **coluna**. Assim causando um ataque ao quadrado corespondente a essa cordenada.
    
  <a name="regras"></a>
  #### Regras:

  - Sempre o primeiro dado jogado sera linha.
  - Quando destruir um dêmonico o quadrado em que ele estava fica **vazio**.
  - Quadrados vazios não tem mais efeitos especiais.
  - Você leva um de dano quando ataca um quadrado vazio na horizontal ou vertical de outro dêmonio.
  - Se sua vida chegar a zero você perde.
  
<a name="elementos"></a>
# Elementos:
 - ![Minion Demon](https://github.com/Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Minon-Demon.png?raw=true "Minion Demon") **Minion Demon:** Um golpe o mata, receba uma moeda.
 - ![Warrior Demon](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Warrior-Demon.png?raw=true "Warrior Demon") **Warrior Demon:** Dois golpes o mata, receba duas moedas.
  - ![Witch Demon](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Witch-Demon.png?raw=true "Witch Demon") **Witch Demon:** Um golpe o mata, revive outro dêmonio, receba três moedas.
  - ![Explosive Demon](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Explosive-Demon.png?raw=true "Explosive Demon") **Explosive Demon:** Um golpe o mata, destroi outro dêmonio, receba um moeda.
  - ![Column](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Column.png?raw=true "Column") **Column:** Jogue um dado coluna para sofrer o efeito.
  - ![Line](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Line.png?raw=true "Line") **Line:** Jogue um dado linha para sofrer o efeito.
  - ![Direction](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Direction.png?raw=true "Direction") **Direction:** Aponta a direção do quadrado que rebera o efeio.
  - ![Horizontal Power](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Horizontal-Power.png?raw=true "Horizontal Power") **Horizontal Power:** Inicia o jogo sem moedas.
  - ![Vertical Power](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Vertical-Power.png?raw=true "Vertical Power") **Vertical Power:** Inicia com vinte pontos de vida.
  - ![Coin](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Coin.png?raw=true "Coin") **Coin:** Inicia o jogo sem moedas.
  - ![Hit Points](https://github.com//Dilumo/Destroyer-of-demonic-hordes/blob/master/Documents/Assets/Hit-Points.png?raw=true "Hit Points") **Hit Points:** Inicia com vinte pontos de vida.



Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email.  As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually* written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.

### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [markdown-it] - Markdown parser done right. Fast and easy to extend.
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [Breakdance](http://breakdance.io) - HTML to Markdown converter
* [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ npm run predeploy
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md] [PlDb] |
| Github | [plugins/github/README.md] [PlGh] |
| Google Drive | [plugins/googledrive/README.md] [PlGd] |
| OneDrive | [plugins/onedrive/README.md] [PlOd] |
| Medium | [plugins/medium/README.md] [PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md] [PlGa] |


### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```
### Docker
Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 80, so change this within the Dockerfile if necessary. When ready, simply use the Dockerfile to build the image.

```sh
cd dillinger
docker build -t joemccann/dillinger:${package.json.version}
```
This will create the dillinger image and pull in the necessary dependencies. Be sure to swap out `${package.json.version}` with the actual version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on your host. In this example, we simply map port 8000 of the host to port 80 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart="always" <youruser>/dillinger:${package.json.version}
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
127.0.0.1:8000
```

#### Kubernetes + Google Cloud

See [KUBERNETES.md](https://github.com/joemccann/dillinger/blob/master/KUBERNETES.md)


### Todos

 - Write MOAR Tests
 - Add Night Mode

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
