# :star2: DataFormsJS Static Files

**Thanks for visiting!** 🌠👍

* __DataFormsJS__: [https://www.dataformsjs.com/](https://www.dataformsjs.com/)
* __CDN (AWS CloudFront)__: [https://d2xbd92kui7v97.cloudfront.net/](https://d2xbd92kui7v97.cloudfront.net/)
* __S3__: [http://dataformsjs.s3-website-us-west-1.amazonaws.com/](http://dataformsjs.s3-website-us-west-1.amazonaws.com/)

<table>
  <tbody>
    <tr>
      <td><strong>en - English</strong><br> This repository contains document images and other files for DataFormsJS. Images are located here to keep the download of the main site and framework small. Images are uploaded from here to a CDN.</td>
    </tr>
    <tr>
      <td lang="es"><strong>es - Español</strong><br> Este repositorio contiene imágenes de documentos y otros archivos para DataFormsJS. Las imágenes se encuentran aquí para mantener pequeña la descarga del sitio principal y el marco. Las imágenes se cargan desde aquí a un CDN.</td>
    </tr>
    <tr>
      <td lang="pt-BR"><strong>pt-BR - Português (do Brasil)</strong><br> Este repositório contém imagens de documentos e outros arquivos para DataFormsJS. As imagens estão localizadas aqui para manter pequeno o download do site principal e da estrutura. As imagens são carregadas daqui para uma CDN.</td>
    </tr>
    <tr>
      <td lang="ja"><strong>ja - 日本語</strong><br> このリポジトリには、DataFormsJSのドキュメントイメージとその他のファイルが含まれています。 メインサイトとフレームワークのダウンロードを小さく保つために、画像はここにあります。 画像はここからCDNにアップロードされます。</td>
    </tr>
    <!--
    <tr>
      <td lang="{iso}"><strong>{iso} - {lang}</strong><br> {content}</td>
    </tr>
    -->
  </tbody>
</table>

## :handshake: Contributing

When submitting changes rename and upload image files as a new file name with the date, rather than deleting a file. This allows older content to still reference the original file and prevents caching issues when using the CDN.

### Example:
* __Original File__: doc/test/file.png
* __New File__: doc/test/file.YYYYMMDD[a-z].png
* __Example 1__: doc/test/file.20191231a.png
* __Example 2__: doc/test/file.20191231b.png

A suffix of [a, b, c, etc] can be added after the date when multiple version of the file are published on the same date. If changes are made on many files in a directory/folder simply upload a new directory [doc/test/v2].

## :art: Sketch App Design File

Workflow for the Sketch files (*.sketch) is not yet decided on. Changes will likely be published to the same file however git would treat is as binary so a cloud service needs to be setup in the future for design changes. Some possibilities:

* <a href="https://www.sketch.com/docs/sketch-cloud/" target="_blank">https://www.sketch.com/docs/sketch-cloud/</a>
* <a href="https://www.invisionapp.com/" target="_blank">https://www.invisionapp.com/</a>
* <a href="https://plantapp.io/" target="_blank">https://plantapp.io/</a>
* <a href="https://kactus.io/" target="_blank">https://kactus.io/</a>

Alternative - Switch to Figma which is browser based

* <a href="https://www.figma.com/" target="_blank">https://www.figma.com/</a>

Until workflow is decided on changes to the (*.sketch) file will not be accepted. Only the current maintainer can edit it. If you are working on new or changed graphics please submit an individual Sketch file for it.

In case you are not familiar with Sketch it’s a widely used Mac-only Application for drawing User Interfaces and Web/App Graphics. It’s used for DataFormsJS to draw most of the SVG Graphics. Here are a few screenshots:

![Sketch - Rocketship](https://raw.githubusercontent.com/dataformsjs/static-files/master/img/screenshots/Sketch-Computer.png)

![Sketch - Icons](https://raw.githubusercontent.com/dataformsjs/static-files/master/img/screenshots/Sketch-Icons.png)

## :memo: License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

All image and artwork files (*.sketch, *.png, *.ico) are dual licensed under both **MIT License** and <a href="https://creativecommons.org/licenses/by/4.0/" target="_blank" style="font-weight:bold;">Creative Commons Attribution 4.0 International License</a>.
