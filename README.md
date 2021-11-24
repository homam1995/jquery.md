# Downloading jQuery

Compressed and uncompressed copies of jQuery files are available. The uncompressed file is best used during development or debugging; the compressed file saves bandwidth and improves performance in production. You can also download a sourcemap file for use when debugging with a compressed file. The map file is not required for users to run jQuery, it just improves the developer's debugger experience. As of jQuery 1.11.0/2.1.0 the //# sourceMappingURL comment is not included in the compressed file.

To locally download these files, right-click the link and select "Save as..." from the menu.



# What you need to build your own jQuery
To build jQuery, you need to have the latest Node.js/npm and git 1.7 or later. Earlier versions might work, but are not supported.

For Windows, you have to download and install git and Node.js.

macOS users should install Homebrew. Once Homebrew is installed, run brew install git to install git, and brew install node to install Node.js.

Linux/BSD users should use their appropriate package managers to install git and Node.js, or build from source if you swing that way. Easy-peasy. 


# How to build your own jQuery
First, clone the jQuery git repo.

Then, enter the jquery directory and run the build script:
```
cd jquery && npm run build
```
The built version of jQuery will be put in the `dist/` subdirectory, along with the minified copy and associated map file.

If you want to create custom build or help with jQuery development, it would be better to install grunt command line interface as a global package:

npm install -g grunt-cli
Make sure you have `grunt` installed by testing:
```
grunt -V
```

Now by running the `grunt` command, in the jquery directory, you can build a full version of jQuery, just like with an npm `run build` command:
```
grunt
```
There are many other tasks available for jQuery Core:
```
grunt -help
```
# قم بتنزيل مكتبة jquery ، الخطوات كالتالي:
1. بحث https://jquery.com/
2.![12](https://user-images.githubusercontent.com/92294739/143006395-026c79d1-e24a-4a13-aa22-e5d2804314a7.png)
3.![13](https://user-images.githubusercontent.com/92294739/143199336-8c03f71a-545f-4338-bf5d-94f004a49d57.png)
4.اختر الإصدار الذي تريده
5.اخترت الأولى وبدأت للتو في التعلم
6. انقر فوقhttps://code.jquery.com/jquery-3.3.1.min.js
7. ![15](https://user-images.githubusercontent.com/92294739/143201072-118f142c-8d91-4987-9b44-de75712109d7.png)
8. ثم اضغط على Ctrl + s لحفظه في الكمبيوتر ويمكن استخدامه.






