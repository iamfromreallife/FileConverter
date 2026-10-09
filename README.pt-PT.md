# File Converter

## Descrição

O **File Converter** é uma ferramenta simples que permite converter e comprimir um ou vários ficheiros através do menu de contexto do Explorador de Ficheiros do Windows.

![Utilização do File Converter](Resources/FileConverterUsage.gif)

Pode transferir a aplicação em [file-converter.io](https://file-converter.io/?from=readme.md).

Para obter mais informações sobre as funcionalidades e a utilização do File Converter, consulte a [wiki do projeto](https://github.com/Tichau/FileConverter/wiki).

## Donativos

O File Converter é um projeto pessoal de código aberto iniciado em 2014. Foram dedicadas centenas de horas ao desenvolvimento, aperfeiçoamento e otimização da aplicação, com o objetivo de tornar a conversão e a compressão de ficheiros simples para todos.

Pode apoiar o projeto [contribuindo para o desenvolvimento](https://github.com/Tichau/FileConverter/wiki#contribute), [fazendo um donativo](https://www.paypal.com/donate/?cmd=_donations&business=3BDWQTYTTA3D8&item_name=File+Converter+Donations&currency_code=EUR&Z3JncnB0=) ou [deixando uma mensagem de agradecimento](https://saythanks.io/to/Tichau).

## Resolução de problemas

Se encontrar algum problema com o File Converter:

- Consulte os problemas já conhecidos na [secção de resolução de problemas da documentação](https://github.com/Tichau/FileConverter/wiki/Troubleshooting).
- Em alternativa, [comunique o problema no GitHub](https://github.com/Tichau/FileConverter/issues).

## Configurar o ambiente de desenvolvimento

### Requisitos

Para o File Converter e a respetiva extensão do Explorador de Ficheiros:

- Visual Studio 2022

Para o instalador:

- [WiX 5](https://wixtoolset.org/) (instalado através do NuGet)
  - [Extensão Community para o Visual Studio](https://marketplace.visualstudio.com/items?itemName=FireGiant.FireGiantHeatWaveDev17)
- [Windows SDK Signing Tools for Desktop Apps](https://developer.microsoft.com/fr-fr/windows/downloads/windows-10-sdk)

## Agradecimentos

Obrigado a todos os colaboradores do projeto File Converter.

### Localização

- Obrigado a **Khidreal** e **hugok79** pela localização em português.
- Obrigado a **Marhc** pela localização em português do Brasil.
- Obrigado a **Chachak** pela localização em espanhol.
- Obrigado a **Davide** pela localização em italiano.
- Obrigado a **nikotschierske** pela localização em alemão.
- Obrigado a **Snoopy1866** pela localização em chinês simplificado.
- Obrigado a **MayaC0re** pela localização em turco.
- Obrigado a **vishveshjain** pela localização em hindi.
- Obrigado a **Mahmoud0Sultan** pela localização em árabe.
- Obrigado a **Sedimentary-Rock**, **NeKoOuO** e **PeterDaveHello** pela localização em chinês tradicional.
- Obrigado a **CrisBalGreece** pela localização em grego.
- Obrigado a **AshiVered** pela localização em hebraico.
- Obrigado a **MrHero118** e **Mehrdad32** pela localização em persa.
- Obrigado a **crnobog69** pelas localizações em sérvio.
- Obrigado a **oogamiyuta** pela localização em japonês.
- Obrigado a **AidyTheWeird** pela localização em checo.
- Obrigado a **Alanimdeo** pela localização em coreano.
- Obrigado a **vrykolakas166** e **thaovd** pela localização em vietnamita.
- Obrigado a **iliamak** pela localização em russo.
- Obrigado a **itsmefdil** pela localização em indonésio.
- Obrigado a **hamzaharoon1314** pela localização em urdu.
- Obrigado a **Zyvrec7** e **stohlferenc** pela localização em húngaro.
- Obrigado a **Maerek** e **MrPrince419** pela localização em polaco.
- Obrigado a **rkalitta** pela localização em sueco.

## Componentes de terceiros

O File Converter utiliza os seguintes componentes:

- **FFmpeg** (v8.0.1) para conversão de ficheiros. [Site oficial](https://ffmpeg.org)
- **ImageMagick** (v14.10) para edição e conversão de imagens. [Site oficial](http://imagemagick.net). Obrigado a dlemstra pelo wrapper para C#. [GitHub](https://github.com/ImageMagick/ImageMagick)
- **Ghostscript** (10.02.1) para processamento de ficheiros PDF. [Transferências](https://www.ghostscript.com/download/gsdnld.html)
- **SharpShell** para criar extensões do menu de contexto do Windows. [GitHub](https://github.com/dwmkerr/sharpshell)
- **Ripper** e **yeti.mmedia** para extração de áudio de CD. [Projeto no CodeProject](https://www.codeproject.com/Articles/5458/C-Sharp-Ripper)
- **Markdown.Xaml** para apresentar Markdown na aplicação WPF. [GitHub](https://github.com/theunrepentantgeek/Markdown.Xaml)
- **WpfAnimatedGif** para apresentar GIFs animados na aplicação WPF. [GitHub](https://github.com/XamlAnimatedGif/WpfAnimatedGif)

## Licença

O File Converter é distribuído ao abrigo da licença GPL versão 3. Para mais informações, consulte o ficheiro `LICENSE.md` na pasta de instalação ou o [site da GNU](https://www.gnu.org/licenses/gpl.html).
