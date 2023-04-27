# Zukunftstag 2023



## Github

- https://github.com/signup
- `username` aussuchen und merken



## VS Code

- Ordner erstellen `username.github.io`

- Ordner in VS Code ziehen

- Auf Github veröffentlichen klicken

- Files erstellen:

  - `index.html`

    - ```html
      <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
      <html>
        <head>
          <title>👋 Hallo Zukunftstag</title>
          <link rel="stylesheet" href="style.css" />
        </head>
        <body>
          <div class="container">
            <h1>👋 Hallo Zukunftstag</h1>
            <img class="portrait" src="me.png" />
            <p>Hello World, ich bin Felix!</p>
          </div>
        </body>
      </html>
      ```

  - `style.css`

    - ```css
      @import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
      
      html,
      body {
        font-family: Roboto;
        min-width: 100vw;
        min-height: 100vh;
      }
      
      .container {
        padding: 50px;
      }
      
      .portrait {
        margin: 20px 0;
        border-radius: 100%;
        max-width: 150px;
        max-height: 150px;
        transition: all;
        transition-duration: 500ms;
      }
      
      .portrait:hover {
        transform: rotate(1turn);
        scale: 1.3;
      }
      
      ```

      

  - Profilbild / Portrait erstellen: https://labs.openai.com/

    - Prompt Beispiel: `blonder web developer der eine brille trägt und einen kaffee trinkt`
    - Bild speichern unter `me.png`

- Über Source Control die Files "stagen", "committen" und "pushen"



