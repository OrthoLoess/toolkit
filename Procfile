web: pip install . -U && toolkit-run

deploy_heroku:
     runs-on: ubuntu-latest
     steps:
       - uses: actions/checkout@v2
       - uses: akhileshns/heroku-deploy@v3.0.4 # This is the action
         with:
           heroku_api_key: ${{secrets.HEROKU_API_KEY}}
           heroku_app_name: "toolkit-34775" # Must be unique in Heroku
           heroku_email: "mail@ratship.net"
