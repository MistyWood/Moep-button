# Moep Button

Moep Button [Click here to visit https://mistywood.github.io/button/](https://mistywood.github.io/button/)

[![Build Status](https://travis-ci.org/MistyWood/Moep-button.svg?branch=master)](https://travis-ci.org/MistyWood/Moep-button)

Related Links:

* [Moeka Koizumi's Twitter](https://twitter.com/k_moeka_)

## Contributing

Please fork this project for modification, and after completing the modification, initiate a Pull Request in this project.

### Add or modify voice

**Description**: All voice meta information is stored in [src/voices.json](src/voices.json). To add or modify these voices, you need to modify this file accordingly.

Voice is always in mp3 format and stored in [public/voices](public/voices). The corresponding URL is `voices/`.

For new voice, please use software such as MP3GainGUI for volume standardization. Currently the volume standardized value is 80.

Because this site uses a strong cache strategy, except for `index.html`, files with the same filename, even if modified, will **NEVER** be refreshed by the client. Therefore, the filename of the newly voice, whatever it is new or modified, **MUST** be different from any previous filename.

If you are modifying voice, delete the original file after modification.

### Participate in translation

Please help us translate to English and Japanese!

The language files for the main program are in three .js files named the language name in [src/locales](src/locales).

The language files for voices are in [src/voices.json](src/voices.json).

The corresponding modification can be recognized by the program as a valid translation.

## Deploying a local development environment

This site is developed using Vue + jQuery + Bootstrap 3.

To deploy a local development environment, first install the latest version of Node. Then follow these steps:

1. Clone the code.

2. Go to the code directory and run `npm install`.

3. Run `npm run serve`. During the code modification process, this local development server can immediately reflect the results of the modification.

4. To compile the files for deployment, run `npm run build`, which will generate the `dist` directory. This site is completely static, you can directly deploy the entire `dist` directory.

> To contribute your code to this project, you don't have to compile locally. After passing the test in the development server and pushing it to Github, you can directly require a Pull Request to this project.

## LICENCE

This project is a work of fans and is not related to the official.

## Special Thanks

This project is supported by MeowSound Idols.

This project is modified based on the [aqua button](https://github.com/zyzsdy/aqua-button).



# Moep Button

Moep Button [Click here to visit https://mistywood.github.io/button/](https://mistywood.github.io/button/)

[![Build Status](https://travis-ci.org/MistyWood/Moep-button.svg?branch=master)](https://travis-ci.org/MistyWood/Moep-button)

Related Links:

* [Moeka Koizumi's Twitter](https://twitter.com/k_moeka_)

## 参与完善本项目

请Fork本项目进行修改，完成修改后在本项目中发起一个Pull Request。

### 添加或修改音频

**简述**：所有的音频信息都存储在[src/voices.json](src/voices.json)中，要添加或修改音频，你需要对应的修改这个文件。

音频一律为mp3格式，存储在[public/voices](public/voices)中。对应的URL为`voices/`。

添加的新音频请先进行音量标准化。可以使用MP3GainGUI之类的软件，目前音量全部标准化为80。

由于本站采用强缓存策略，除`index.html`外，文件名一致的文件，即使修改也**永远**不会被客户端刷新。因此新添加的音频，无论是新增还是修改，文件名都**必须**和之前任何文件名都不同。

如果是修改音频，请在修改之后删除原音频文件。

### 参与翻译

请帮助进行英文和日语的翻译！

主程序翻译在 [src/locales](src/locales) 中的三个以语言名命名的js文件中。

语音的翻译在 [src/voices.json](src/voices.json) 中。

### 参与网页开发

请参考[部署本地开发环境](#部署本地开发环境)一节。

## 部署本地开发环境

本站使用 Vue + jQuery + Bootstrap 3 开发。

要部署本地开发环境，请先安装最新版的node。然后按照如下步骤操作：

1. Clone代码到本地。

2. 进入代码目录，运行`npm install`。

3. 运行本地开发服务器`npm run serve`，在代码修改过程中，本地开发服务器可以即时反映修改的结果。

4. 要编译可供部署的文件，请运行`npm run build`，这会生成`dist`目录。本站为全静态，将整个`dist`目录部署即可。

若要为本项目贡献你的代码，你不必在本地编译。在开发服务器中测试通过并推送至Github后，直接给本项目提交Pull Request即可。

## LICENCE

程序部分： MIT

本项目为爱好者作品，和官方没有关联

## Special Thanks

This project is supported by MeowSound Idols.

This project is modified based on the [aqua button](https://github.com/zyzsdy/aqua-button).


