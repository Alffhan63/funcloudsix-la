We want to understand how you think like a devops or system engineer, and the level of craft you bring to
bear when building and running monitoring system and knowledge about logging.

Please note that not following the instructions below and taking longer than the time allocated
will negatively affect our evaluation of your submission.

Rules

You have a maximum of 3 full days to implement a solution (the sooner the better).

Please attach your configuration and create instruction how to running and give explanation in the README file

More initiative will positively affect our evaluation.

environment :

source test : github.alfhan.linkaja.com

grafana : grafana-linkaja-test.linkaja.com

username : your complete name without space ex : alfhanrizkyfauzan

password : Link3TestCAseL2

loki : grafana-linkaja-test-log.linkaja.com



Goals

we have goals how monitoring service from logging service as datasource, and we create alert, threshold and sure show at grafana.

we have example log from source test, name file is result.log.

please send thats log to our grafana and create a dashboard with the following :

using prometail for agent to send the log with filename and label is yournamecompletename ( please attach this configuration on README )

ex :

labels:
      name : Your complete name without space
      path: /$pwd/Yourname/grafana/result.log

##example
labels:
      name : alfhanrizkyfauzan
      path: /$pwd/alfhanrizkyfauzan/grafana/result.log

at grafana please create a dashboard and show the title and vote_average as a legend

last is show last and total data at tabel values

please give name your dashboard and your panel with your complete name without space



2. we have goals to monitoring metrics in our kubernetes enviroment.

please create the monitoring metric stack using prometheus with the follow :

using kubernetes at minikube, kind or etc ( please provide this configuration and step on README )

show or screenshoot graph on prometheus server dashboard and show one of metrics that can be scraped by prometheus ( memory or cpu or etc ).



Submission
Once you're done, please send the following information:

 Code repository URL (Github/ Bitbucket/ Gitlab, etc.), make sure to make it publiclyaccessible or send all configuration at mail.

if anything question or information please fajar_hadiyanto@linkaja.id
# funcloudsix-la
