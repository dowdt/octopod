# Contact Central? 
## (Taking suggestions for better name)

# NOT FINISHED USE AT YOUR OWN RISK

An encrypted database for contacts.
With scriptable hooks to social media and other services.

## Vision


## Planned Features


## Current Features


## Architecture


## Extending and plugins

## Config file

```

# start line with # for comment, empty lines are ignored

provider:
    id: "phone"
    display_name: "Phone Number"
    script: ""

provider:
    id: "twitter"
    display_name: "Twitter"
    dm_url: "https://twitter.com/{{cuid}}-{{uid}}"
    pub_url: "https://twitter.com/{{cuid}}"

provider:
    id: "facebook"
    display_name: "Facebook"
    dm_url: "https://www.facebook.com/messages/t/{{cuid}}/"
    pub_url: "https://www.facebook.com/profile.php?id={{cuid}}"

provider:
    id: "whatsapp"
    display_name: "Whatsapp"
    dm_url: "https://web.whatsapp.com"
    pub_url: "https://web.whatsapp.com"

```
