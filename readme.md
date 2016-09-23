# ReadMe

This is the SinnerSchrader "s2 Website" Project.

## Starting the Prototype Server

### Get the most stable NodeJS-Server

```shell
nave use stable
```

### Install all NodeJS modules and grunt-cli for build tools

```shell
npm install
npm run build:all
```

This step is only required once.

### Run the Server

```shell
npm run serve
```

open [http://localhost:3000]()

### Build process (watch tasks)

```shell
npm run build:watch
npm run serve
```

Afterwards open your editor and start hacking.

------------------------------------------------------------------

## Browsermatrix

The projects supports the S2 default Browsermatrix:

* Desktop
* - Chrome, Safari, Opera, Firefox, IE: current and previous
* Mobile
* - Android, iOS, IEMobile: current and previous
* - NO Blackberry and no Android stock browsers

## Used PreProcessors

* LessCSS for CSS

### Included Libs are

* Less v2.x.x

### Used PostProcessors

* Autoprefixer for CSS (NodeJS and Grunt)
* ClosureCompiler and Uglify for JS/CSS (Grunt)
