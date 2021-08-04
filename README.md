# manga2pdf
Simple script to download and merge manga images into a single pdf file. Uses Ruby and Selenium.
Works with manga from Manganato.
It's currently WIP and in a very early stage.

### Requirements
* Ruby 2.7
* selenium-webdriver 4.0 (currently in beta)
* firefox-geckodriver
* ruby-progressbar

### Usage
Launch the script like this:
```bash
ruby manga2pdf.rb -u <url> [-d] [-l 10]
```
* -u is for the url 
* -d is to create individual directories for each volume.
* -l is to limit the number of chapters downloaded. The number after -l is the number of chapters to download.
