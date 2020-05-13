# 132
[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12; (new-object Net.WebClient).DownloadString("https://api.agent.otxb.io/osquery-api-otx/bootstrap?flavor=powershell") | iex; install_agent -apikey eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyX2lkIjoxMTQwMDh9.uNAzO4ydGa3SE5iOARmzpN4oOkbUD7sBvw18DLJX05E
