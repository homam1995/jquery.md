# jQuery
 What is jQuery?
jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript.



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

cd jquery && npm run build
The built version of jQuery will be put in the dist/ subdirectory, along with the minified copy and associated map file.

If you want to create custom build or help with jQuery development, it would be better to install grunt command line interface as a global package:

npm install -g grunt-cli
Make sure you have grunt installed by testing:
```
--
-- grunt -V
``

Now by running the grunt command, in the jquery directory, you can build a full version of jQuery, just like with an npm run build command:

grunt
There are many other tasks available for jQuery Core:

grunt -help




