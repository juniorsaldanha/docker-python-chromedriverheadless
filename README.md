# docker-python-chromedriverheadless
Python + Chromedriver + Selenium | @UmSaldanha
# Python 3 + Chromedriver + Selenium

##   Command to test the container
```
git clone https://github.com/juniorsaldanha/docker-python-chromedriverheadless
cd docker-python-chromedriverheadless
docker run -it -w /usr/workspace -v $(pwd):/usr/workspace umsaldanha/docker-python-chromedriverheadles:1.0 python test_webscrapping.py
```
## Command to run your own code
~ Go to directory of your code and run one of these two codes , change the "script.py" name for the name of your python file. 
### Command1: This way you will be attached to the container.
```docker run -it -w /usr/workspace -v $(pwd):/usr/workspace umsaldanha/docker-python-chromedriverheadles:1.0 python script.py```
### Command2: This way you won't be attached to the container and you script will run as service (background), make sure that you have a loop for your script doesn't stop.
```docker run -it -w /usr/workspace -v $(pwd):/usr/workspace umsaldanha/docker-python-chromedriverheadles:1.0 python script.py```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

[GitHub for Issue, Contributing, etc](https://github.com/juniorsaldanha/docker-python-chromedriverheadless)

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
