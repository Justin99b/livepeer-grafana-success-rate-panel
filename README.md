# livepeer-grafana-success-rate-panel
This allows you to add a Panel to show your current success rate using a currently available api of the [Interptr Test Stream Inspector](https://interptr-latest-test-streams.vercel.app/)

![image](https://user-images.githubusercontent.com/17692991/139015780-462e9865-6131-424d-afa9-900cbbb83afb.png)


You need the [JSON API](https://grafana.com/grafana/plugins/marcusolsson-json-datasource/) Plugin for Grafana
Here the config for the Data Source:

# Config

URL: `https://leaderboard-serverless.vercel.app/api/raw_stats`
<br/>
Query string `orchestrator=YOUR_ORCHESTRATOR_ADDRESS`

![image](https://user-images.githubusercontent.com/17692991/139015432-a608bc24-c2b4-438b-8e99-7fd1549130c8.png)
