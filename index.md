---
layout: full
body_class: home
menu_item: getting_started
---

## Install NodeGit

NodeGit can be quickly and painlessly installed via NPM. For more
comprehensive installation techniques, check out the
[Install Guides](/guides/install/).

```bash
npm install nodegit
```

* * *

## Compatibility

<div class="columns compatibility">
  <div class="column">
    <h3>Native Shells</h3>
    <div class="columns">
      <div class="column">
        <a href="http://github.com/atom/atom-shell">
          <img src="/img/atom.png"/> Atom
        </a>
      </div>
      <div class="column">
        <a href="http://nwjs.io">
          <img src="/img/nwjs.png"/> nw.js
        </a>
      </div>
    </div>
  </div>
  <div class="column">
    <h3>Operating systems</h3>
    <div class="columns">
      <div class="column">
        <a href="http://apple.com/osx">
          <img src="/img/osx.png"/> OS X
        </a>
      </div>
      <div class="column">
        <a href="http://microsoft.com/windows">
          <img src="/img/windows.png"/> Windows
        </a>
      </div>
      <div class="column">
        <a href="http://linux.com">
          <img src="/img/linux.png"/> Linux
        </a>
      </div>
    </div>
  </div>
  <div class="column">
    <h3>Node support</h3>
    <div class="columns">
      <div class="column">
        <a href="http://nodejs.org">
          <img src="/img/nodejs.png"/> NodeJS
        </a>
      </div>
      <div class="column">
        <a href="https://iojs.org">
          <img src="/img/iojs.png"/> io.js
        </a>
      </div>
    </div>
  </div>
</div>

* * *

## Getting Started

You simply need to require NodeGit in your project to start using it.

``` javascript
var Git = require("nodegit");
```

### <a name="clone-a-repository"></a>Clone a Repository

Let's learn how to clone a repository. Create a file named `clone.js`,
and add the following code:

``` javascript
Git.Clone("https://github.com/nodegit/nodegit", "tmp").then(function(repository) {

});
```

### <a name="open-a-repository"></a>Open a Repository

Let's learn how to open a repository. Create a file named `open.js`,
and add the following code:

``` javascript
Git.Repository.open("tmp").then(function(repository) {

});
```

* * *

## <a name="brought-to-you-by"></a>Brought to you by

NodeGit is brought to you by the work of [many contributors](https://github.com/nodegit/nodegit/graphs/contributors) all over the globe. We are proud to be sponsored by the following companies to continue work on making NodeGit one of the best native node modules around!

<div class="columns logos">
  <div class="column">
    <a class="axosoft" target="_blank" href="https://axosoft.com">
      <img src="/img/axosoft.png">
    </a>
  </div>
  <div class="column">
    <a class="github" target="_blank" href="https://github.com">
      <img src="/img/github.png">
    </a>
  </div>
  <div class="column">
    <a class="bocoup" target="_blank" href="https://bocoup.com">
      <img src="/img/bocoup.png">
    </a>
  </div>
</div>