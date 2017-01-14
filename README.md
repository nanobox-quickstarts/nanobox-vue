![Vue from scratch](https://guides.nanobox.io/assets/quickstart-icons/vue.png)

# Vue from scratch

Run a Vue app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-vue.git

# cd into the vue app
cd nanobox-vue
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local vue.dev

# Run vue as you would normally, with Nanobox
nanobox run npm run dev --host 0.0.0.0
```

## Check it out

Visit your app at <a href="http://vue.dev" target="\_blank">vue.dev</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# your packages are available,
npm list

# and your code is mounted
ls
```

## Now What?
For more details about running vue apps with nanobox visit [guides.nanobox.io/nodejs/vue/](https://guides.nanobox.io/nodejs/vue/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
