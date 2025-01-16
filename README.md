# Station Ratings

```
pip install -r requirements.txt
brew install --cask wkhtmltopdf
jupyter nbconvert --to html east-central-line-stations.ipynb --no-input
wkhtmltopdf --page-height 10000mm east-central-line-stations.html east-central-line-stations.pdf
```

(you'll probably also need to get the tube font if you want it and update the font cache)