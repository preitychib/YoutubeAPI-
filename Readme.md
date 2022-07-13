# Getting Started

In order to run this project you have to follow the following steps:

- clone the Repository
- create a new folder for managing virtual environments and create a new virtual environment using 'venv' as `python -m venv yt-env`
- activate virtual environment as

```zsh
# for linux use
source <location-to-virtual-environment>/YoutubeAPI/bin/activate

# for windows use
<location-to-virtual-environment>/YoutubeAPI/Scripts/activate
```

- cd into the cloned repo
- run `poetry install` to install all needed deps

# Do not forget to add your credentials

- Create `client_secrets.json` file
- Copy the following code and fill your credentails

```{
  "web": {
    "client_id": "[[INSERT CLIENT ID HERE]]",
    "client_secret": "[[INSERT CLIENT SECRET HERE]]",
    "redirect_uris": [],
    "auth_uri": "https://accounts.google.com/o/oauth2/auth",
    "token_uri": "https://accounts.google.com/o/oauth2/token"
  }
}
```

## Cheers :)
