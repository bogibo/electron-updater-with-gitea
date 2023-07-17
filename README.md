# electron-updater-with-gitea

This is the fork of electron-updater which include Gitea provider.<br>
The Github provider has been changed to work with Gitea.<br>
It's only work with Gitea v1.19.x. 

## Usage

Use 'github' as provider name.

In package.json

``` 
     "win": {
       "publish": {
        "provider": "github",
        "host": "your_host_name",
        "owner": "repo_owner",
        "repo": "repo_name",
        "private": true,
        "token": "your_personal_access_token"
      }
      ...
     }
 ```
