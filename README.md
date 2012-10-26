## Instapaper Fluid

<img src="https://raw.github.com/jordanandree/instapaper-fluid/master/screenshot.png" width="300px" align="right" />


Instapaper Userstyles for [Fluid](http://fluidapp.com/) to make Instapaper more "App-like". Allows you to have a dedicated app that simply skins the Instapaper account page where you can view all of your saved articles. 

### Requirements

* Fluid Mac OS App - [http://fluidapp.com](http://fluidapp.com)
* Instapaper Account - [http://instapaper.com](http://instapaper.com)

### Setup

* Open up Fluid and you should be prompted to create a Fluid App
* Set the fields to:
	* URL: http://instapaper.com/u 	
	* Name: Instapaper
	* Location: Applications
	* Icon: You can download from the [Press Page](http://www.instapaper.com/press-kit)
* After the App is created, Open it and navigate from the menu bar to Window > Userstyles
* Add a new group from the bottom left "+" button, name it Instapaper
* Add a new pattern with it matching `*instapaper.com*`)
* Copy + Paste the `userstyles.css` file contents into the css text area
* Optionally, you can add the `userscripts.js` file contents following the same process from Window > Userscripts in menu bar. The script simply reloads the page every 15 minutes.