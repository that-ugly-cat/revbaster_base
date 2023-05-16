# RevMaster documentation
# (still under heavy development, to be considered an alpha version)
## Installation
- Fork this git repo
- Add to this repo your firestore key json file (not a best practice, to be changed soon, use an expendable firebase account)
- Generate a new [personal access token (classic)](https://github.com/settings/tokens) - more info [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- Note down your username, repo name and access token 
- Create a new streamlit app and connect it to the newly forked repo
- Paste the following info in the streamlit app's (secrets)[https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app/connect-to-data-sources/secrets-management]:
  - github_user = 'your username'
  - github_repo = 'your repo'
  - github_token = 'your token'
- launch the app and go through the setup process
  - ...
