Files from An Introduction to Elasticsearch and Kibana for Data Scientists

  virtualenv dsenv  # whatever version of python is fine so long as it's python 3, but it might work on earlier versions too
  . dsenv/bin/activate
  pip install -r requirements.txt
  # now edit env.sh and put in your Elastic Cloud Elasticsearch Endpoint URL and Password if you're gonna use Cloud
  . env.sh && jupyter notebook

Then open the notebook! The source Airbnb listings dataset is in this folder already.

