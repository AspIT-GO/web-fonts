# Web fonts

[Github page: Web fonts](https://aspit-go.github.io/web-fonts/)

## Eksempler

```CSS

/* Font embedded fra Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap');

.indie-flower-regular {
  font-family: "Indie Flower", cursive;
  font-weight: 400;
  font-style: normal;
}

/* Font fra web-server */
@font-face {
  font-family: "Inconsolata";
  src: url(./assets/fonts/Inconsolata_Condensed-Regular.ttf);
}
@font-face {
  font-family: "Inconsolata";
  src: url(./assets/fonts/Inconsolata_Condensed-Black.ttf);
  font-weight: 500;
}

.inconsolata-regular {
  font-family: "Inconsolata";
  font-weight: 400;
  font-style: normal;
}

.work-sans-regular {
  font-family: "Work Sans", sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
}

/* Font fra web-server med variable font */
@font-face {
  font-family: "JobClarendon";
  src: url("./assets/fonts/WorkSans-VariableFont_wght.ttf");
  font-weight: 100 900;
}

.jobClarendon-regular {
  font-family: "JobClarendon";
  font-weight: 400;
}

.jobClarendon-bold {
  font-family: "JobClarendon";
  font-weight: 700;
}

```