# Tuinen Peters

### Install

Download the project from GitHub:

```sh
git clone https://github.com/Lokdei/tuinen-peters
```

Download the [roxo theme](https://github.com/StaticMania/roxo-hugo) from GitHub and move it into the /themes/roxo/ folder 

### Setup

Live Mode:

```sh
hugo server --buildDrafts --config config-nl.toml --themesDir ~/Projects/ --theme jardins-peters-roxo
```

Disable LiveReload:

```sh
hugo server --disableLiveReload --config config-nl.toml --themesDir ~/Projects/ --theme jardins-peters-roxo
```

Publish:

```sh
# Nederlands: 
hugo --cleanDestinationDir --config config-nl.toml --themesDir ~/Projects/ --theme jardins-peters-roxo
# Frans: 
hugo --cleanDestinationDir --config /config-fr.toml --themesDir ~/Projects/ --theme jardins-peters-roxo
```
