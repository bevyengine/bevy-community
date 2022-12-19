# bevy-community
A listing of Bevy community members which is displayed on the Bevy website

## Card Format

You can use the following fields in a toml file:

```toml
# Name you want to appear with.
# Mandatory
name = "Me, Myself and I"

# File name of your profile picture if you uploaded one
# If you provide a file, be mindful of its size
# If you also add your github profile, you can use "GitHub" to use your GitHub profile picture
# Optional
profile-picture = "Picture.jpeg"

# Short presentation of yourself
# Optional
bio = ""

# Link to your sponsoring page, GitHub Sponsor, Patreon, Buy Me a Coffee, ...
# Optional
sponsor = ""

# Social links
# They are all optional

## Will link to https://github.com/<username>
github = "username"

discord = "DiscordUsername#1234"
## This allows direct linking to your profile for people with a shared server
## https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-
discord-userid = ""

## Will link to https://<instance.com>/@<username>
mastodon = "@username@instance.com"

## Will link to https://twitter.com/<username>
twitter = "username"

## Will link to https://<username>.itch.io/
itch-io = "username"

## Will link to http://store.steampowered.com/developer/<developer_name>
steam-developer = "developer_name"

## Free link, will be displayed as is
website = "https://mywebsite.com"
```
