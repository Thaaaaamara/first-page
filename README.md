### Códigos de Git

- git status
- git add --all
- git commit -m "mensagem"
- git pull
- git push

# comandos de VSCODE

- ctrl + p => procurar arquivos dentro do projeto

### Comandos de terminal

- cd => navegacao entre pastas
  - cd /home/prog/site1
  - cd / => vai pro diretorio raiz (root - o inicio do sistema)
- cd ../ => voltar uma pasta
- cd ./ => entrar apartir de onde eu estou (apertar tab)
- pwd => mostrar o caminho completo da onde eu estou
- ls -la => mostrar o que tem na pasta que estou agora

### Navegacao entre diretorios

- o ponto de vista de navegacao é sempre o diretorio que estou agora
- ./ => é a forma de escrever "a partir de onde eu estou"
  - ./images/ => "existe uma pasta images dentro da onde eu estou"

### Conceitos basicos de html e css

```css
div.pagina div#menu.background-grey .logo {
}

.container {
}

.comida .container .logo {
}

.color-red {
}

.bebida .logo {
}

.bebida .container .color-red {
}
```

```html
<div id="id_unico" class="my-div" user-name="gio">
  <h1>Ola mundo</h1>
</div>

<div class="comida">
  <div class="container">
    <div class="logo color-red"></div>
  </div>
</div>

<div class="bebida">
  <div class="container">
    <div class="logo color-red"></div>
  </div>
</div>
```

```typescript
// string = "texto"
// number = 24
// boolean = true

// array = []
// object = {}

const userName: string = "Gio";
const userAge: number = 35;
const isBlond: boolean = false;

const userNames: string[] = ["Gio", "Bruno"];

type UserDataType = {
  name: string;
  age: number;
  isBlond: boolean;
};

const userData: UserDataType = {
  name: "Gio",
  age: 35,
  isBlond: true,
};

userData.name;
```
