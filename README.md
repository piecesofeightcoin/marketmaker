http://mm7-mm7.7e14.starter-us-west-2.openshiftapps.com/
https://www.deribit.com/reg-4393.9303

Download, install node, npm (any machine)

git clone https://github.com/DunnCreativeSS/marketmaker

run npm i in the directory of ths git repo

Open deribit.js

Change key, secret to appropriate values

Run on TestNet

When you want to run on livenet, take out the ', 'https://test.deribit.com'' section of var restClient = new RestClient('key','secret'



It should look like:



var restClient = new RestClient('key','secret')
