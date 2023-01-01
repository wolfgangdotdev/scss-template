# SCSS Template

Basic SCSS template for quickly starting a project. Uses several NPM packages alongside custom start and build scripts to automatically compile files to a dist folder. Uses browser-sync to create a live server and watches for changes in html, javascript and SCSS files.

![Screenshot](https://user-images.githubusercontent.com/112465173/210163556-e5c8f21c-63c8-42c8-8317-f4de36f2711e.png)

# Usage

Create a new repository in GitHub using this repo as a template. Clone into newly created repository. From the terminal, run the following command:

```
npm install
```

Node Package Manager will install the required files. Once this is done, run:

```
npm start
```

Your local development server will open in a new browser tab. It will now watch your files for any changes, including recompiling your SCSS files. Once you have finished creating your website, run:

```
npm run build
```

This will clean out your dist/ folder, recompile all SCSS files, and autoprefix and minify the resulting CSS file. You can now deploy your website to the hosting service of your choice. Be sure to direct your host to the dist/ folder which contains your index.html file, not the root.
