# Cosmic Theme for Hugo

This theme is a fork of the wonderful [Eternity theme](https://github.com/boratanrikulu/eternity) by [Bora Tanrikulu](https://github.com/boratanrikulu), adjusted to my particular use case. Make sure you check it out if you're looking for an easy to use, great looking, and reliable Hugo theme for your website!


### Demo

Website: [eternity.bora.sh](https://eternity.bora.sh)

<div align="center">

https://user-images.githubusercontent.com/20258973/180658086-24069751-1e78-44ef-88aa-21e045ef249d.mp4

</div>


### Features

- **Configurable** features.

- **Multiple images** support.

- Clean, fresh, **minimalist**.

- Integrated **lazy load**.

- Automatically creates **resized** thumbnails.

- Shows **exif** if it exists.

### Installation

1. Install Hugo.

2. Create a new site.  
	```shell
	hugo new site yoursite
	```  
	```shell
	cd yoursite
	```  

3. Remove default config file.  
	```shell
	rm hugo.toml
	```
	If you use an older version of Hugo ([< v0.110.0](https://github.com/gohugoio/hugo/issues/8979)), your config might be called differently:
	```shell
	rm config.toml
	```

4. Submodule the theme.  
	```shell
	git init
	```  
	```shell
	git submodule add --depth=1 https://github.com/boratanrikulu/eternity.git themes/eternity
	```  

5. Create config.yaml;  
	Apply (1) or (2).  

	1. Use the example project (recommended).  
		Copy all files from the example project.  
		```shell
		cp -r ./themes/eternity/example/eternity.bora.sh/* .
		```  
	2. Use empty content.  
		Copy example config.  
		```shell
		cp ./themes/eternity/config.example.yaml ./config.yaml
		```  
6. Start the server.
	```shell
	hugo serve --port 1313
	```  

7. Go to [localhost:1313](http://localhost:1313).

### Upgrade

To get last updates, just git pull.
```shell
cd themes/eternity && git pull && cd -
```

### Usage of Posts

[**Go to posts documentation.**](doc/posts.md)

### Usage of Config.yaml

[**Go to config documentation.**](doc/config.md)

### Editing Style

[**Go to style documentation.**](doc/style.md)

### Contact

If you need to contact us for any reason; create an [**issue**](https://github.com/boratanrikulu/eternity/issues/new) or send a mail to [**eternity@bora.sh**](mailto:eternity@bora.sh).
