### <p align="center"><img width="150px" height="150px" src="icon.png"></p>

# [Pwa](#)

## Installation

1. Clone this repo

  ```bash
  git clone https://github.com/davidsonbpe/pwa-serv
  ```


## Baunilha HTML

2. A maneira mais fácil de começar a usar o PWA é adicionando uma tag de script

 ```bash
  <link rel="manifest" href="./manifest.json" />
  <script src="./pwa.dev.min.js"></script>
  <script> if (navigator.serviceWorker) { navigator.serviceWorker.register ('./sw.js') } </script>
  ```

