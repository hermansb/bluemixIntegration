Get started with nodeAppGitHubTest
-----------------------------------

Welcome to Node JS Web Starter application that uses the IBM DataCache REST interface!

This sample application demonstrates how to write a Node JS application using the IBM DataCache REST interface and deploy it on Bluemix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/bfa3229b-f412-4a0a-89db-369d7436de3b/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u hermanba@ca.ibm.com
		cf target -o hermanba@ca.ibm.com -s dev
		
6. Deploy your app:

		cf push nodeAppGitHubTest

7. Access your app: [http://nodeAppGitHubTest.mybluemix.net](http://nodeAppGitHubTest.mybluemix.net)
