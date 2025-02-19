# chergpt-basic: custom chat assistant
No login, vanilla ChatGPT-like interface with scaffolded code for immediate deployment 
Test deployment for IMH education office

## Features
- [x] Set custom instructions to guide student interactions <br>
- [WIP] Trigger immediate summaries of learning insights at the end of the session <br>

Need to gate access with a simple global password? See [here](https://docs.streamlit.io/knowledge-base/deploy/authentication-without-sso) 

## How to setup backend 
A) **NeonDB** You can follow instructions on NeonDB here: https://start.open.gov.sg/docs/getting-started/prerequisites <br>
B) **CockroachDB** <br>
* Create a CockroachDB Serverless cluster (free)<br>
* Sign up for a CockroachDB Cloud account.<br>
* Log in to your CockroachDB Cloud account.<br>
* On the Clusters page, click Create Cluster.<br>
* On the Create your cluster page, select Serverless.<br>
* Click Create cluster.<br>

Your cluster will be created in a few seconds and the Create SQL user dialog will display.

For either (A) or (B), copy the URL and put it as `DB_CONNECTION = "{DB connection String}"` under `secrets.toml`
