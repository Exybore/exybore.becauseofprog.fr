<div align="center">
  <img src="public/img/avatar.png" width="200px" alt="Avatar"/>
  <h1>Exybore</h1>
  <h3>Personal website which redirects to my links</h3>
  <a href="http://exybore.becauseofprog.fr">exybore.becauseofprog.fr</a>
</div>

- [💻 Developing](#-developing)
- [🔨 Deploying](#-deploying)
- [📜 Credits](#-credits)
- [🔐 License](#-license)

## 💻 Developing
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fexybore%2Fexybore.becauseofprog.fr.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fexybore%2Fexybore.becauseofprog.fr?ref=badge_shield)


First of all, clone the repository on your local drive :

```bash
git clone https://github.com/exybore/exybore.github.io.git  # HTTPS
git clone git@github.com:exybore/exybore.github.io          # SSH
```

Install the dependencies...

```bash
cd exybore.github.io

npm install   # NPM
yarn install  # Yarn
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev  # NPM
yarn dev     # Yarn
```

Navigate to [localhost:5000](http://localhost:5000). You should see the app running !

## 🔨 Deploying

In order to build the application to be production-ready, just use this command :

```bash
npm run build  # NPM
yarn build     # Yarn
```

Then, you just have to serve the `public/index.html` file. That's all !

## 📜 Credits

- Library : [Svelte](https://svelte.dev)
- Maintainer : [Exybore](https://github.com/exybore)

## 🔐 License

[GNU GPL v3](LICENSE)


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fexybore%2Fexybore.becauseofprog.fr.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fexybore%2Fexybore.becauseofprog.fr?ref=badge_large)