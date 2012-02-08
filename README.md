# Stasis Build Pack

The Stasis Build Pack will run `stasis` to create and serve the site.

## Usage

Add this language pack to your `BUILDPACK_URL`.

    heroku config:add BUILDPACK_URL="http://github.com/markpundsack/heroku-buildpack-stasis.git"
    
Or, with a recent version of the heroku gem, set it at creation time:

    heroku create --stack cedar --buildpack http://github.com/markpundsack/heroku-buildpack-stasis.git
