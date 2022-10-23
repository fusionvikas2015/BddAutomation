Commands:

sauceLab
================================================
By Tag Name:
`python runner.py --module sauceLab --tags @Login`
`python runner.py --module sauceLab --tags @invalidlogin`

By Feature Name:
`python runner.py --module sauceLab --features login.feature`
`python runner.py --module sauceLab --features login.feature,dashboard.feature`

By Module Name:
`python runner.py --module sauceLab`

c
sauceLab
================================================
By Tag Name:
`python runner.py --module youtube --tags @youtubeTest`

By Feature Name:
`python runner.py --module youtube --features youtube.feature`

By Module Name:
`python runner.py --module youtube`




Behave Command (sauceLab):
=========================

- `behave .//modules//sauceLab --tags=@validlogin -f allure_behave.formatter:AllureFormatter -o
  reports\BDDAutomation_23102022232145\results -D
  module=sauceLab -D job_id=BDDAutomation_23102022232145`

## Links:

- `GMAIL: https://realpython.com/python-send-email/#:~:text=Set%20up%20a%20secure%20connection,attachments%20using%20the%20email%20package`
- CURl: `https://curl.se/windows/`
- Allure: `https://github.com/allure-framework/allure2/releases`
- Netlify API: `https://docs.netlify.com/api/get-started/`