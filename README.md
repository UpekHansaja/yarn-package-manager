# Yarn Package Manager

---

### What is Yarn?

`Yarn` is a JavaScript Package Manager which created by Facebook (Meta). It is a Fast & Reliable Alternative to `npm` (Node Package Manager).
`Yarn` consists of Similar Syntax & almost Identical functionality to `npm`. But when it comes to `yarn` the commands are a little bit different than the commands in `npm`.

</br>

Yarn installs packages from the NPM Registry, which means anything that you can install with `npm`, can also install with the `yarn`.

Yarn installation can be done in several ways,

<!-- </br> -->

### 01. Using Corepack

- ##### _Step 1.1 - Install `corepack`_

_If you already installed corepack, you can skip this step._

_To install `corepack` using Homebrew (MacOS):_

```sh
brew install corepack
```

or
_To install `corepack` using NPM as a global:_

```sh
npm install -g corepack
```

- ##### _Step 1.2 - `yarn` initialization_

_If you already installed `corepack` then you might like to continue with the following,_

1.  _Start by enabling Corepack, if it isn't already; this will add the yarn binary to your PATH:_

```sh
corepack enable
```

2.  _Then initialize a new project:_

```sh
yarn init -2
```

</br>

---

### 02. Platform Installation

  </br>

- #### _Windows_ ⊞ ------------
  </br>

_2.1 - Download the installer_

Only for Windows users,
[Click Here to download `yarn` package manager as a `msi` installer.](https://classic.yarnpkg.com/latest.msi)

  </br>
    
_*_2.2 - Install via Chocolatey_*_

[Chocolatey](https://chocolatey.org/) is a package manager for Windows.
If you have already installed chocolatey,

```sh
choco install yarn
```

This will also ensure that you have Node.js installed.

</br>

- #### _MAC OS_  -------------

   </br>

_2.1 - Install via Homebrew_

You can install `Yarn` through the [Homebrew](https://brew.sh/) package manager. This will also install Node.js if it is not already installed.

```sh
brew install yarn
```

  </br>

_2.2 - Install via MacPorts_

You can install `Yarn` through MacPorts. This will also install Node.js if it is not already installed.

```sh
sudo port install yarn
```
  </br>

_2.3 - Installation Script_

One of the easiest ways to install `Yarn` on macOS and generic Unix environments is via our shell script.

```sh
curl -o- -L https://yarnpkg.com/install.sh | bash
```

  </br>
    
- #### _Linux_ &nbsp; >_  ---------------

   </br>

_2.1 - Via Debian package repository_

On Debian or Ubuntu Linux, you can install Yarn via our Debian package repository. You will first need to configure the repository:

```sh
curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
```

  </br>

Then you can simply:

```sh
sudo apt update && sudo apt install yarn
```
  </br>

***

### Check installation

  </br>

Check that Yarn is installed by running:

```sh
yarn -v
```

or

```sh
yarn --version
```

***

### Usage

  </br>

Following are the main commands you need to know to kick start with `yarn`.

- Running `yarn` is enough to run an install! It's an alias for `yarn install`.


- Adding or updating a dependency to a single package is done with `yarn add`.


- Upgrading a dependency across the whole project is done with `yarn up`.


- Your scripts are aliased. Calling `yarn build` is the same as `yarn run build`.


- Most registry-related commands are moved behind `yarn npm` (ex: `yarn npm audit`).

</br>

Visit [Yarn CLI reference](https://yarnpkg.com/cli) for further references.