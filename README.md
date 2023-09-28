# Jazz-Shrimp
A method for creating a "help desk on rails" utilizing Okta Workflows as a web server. Based on my talk at JNUC 2023: "Jazz Shrimp: Using Slack Workflows to Automate Jamf Device Management"

# Documentation/Resources

Okta Workflows documentation - https://help.okta.com/wf/en-us/content/topics/workflows/workflows-main.htm

Okta Workflows Connector Builder - https://help.okta.com/wf/en-us/content/topics/workflows/connector-builder/connector-builder.htm

Slack API documentation - https://api.slack.com/docs

Slack Block Kit Builder (Sign in Required) - https://slack.com/workspace-signin?redir=%2Fapi%2F%2Ftools%2Fblock-kit-builder

# JNUC 2023 Presentation 
The VOD of the JNUC 2023 presentation [can be found here](https://reg.rainfocus.com/flow/jamf/jnuc2023/home23/page/sessioncatalog/session/1681930483510001IvM3) for 60 days following the conference end date (September 21, 2023), and like previous years, will probably trickle into YouTube.

# What is this?
"Jazz Shrimp" is based on an emoji found in Slack. A "slackmoji", if you will (https://slackmojis.com/). **TL;DR** I needed to automate/facilitate the need to fulfill escalted requests from my helpdesk team to enable them to Self Service requests such as email delegations/GAM functions, password resets, device locks/other MDM commands, etc. I have a programming background but didn't have the time or resources to develop something internally.

Enter Jazz Shrimp. A helpdesk on rails implemented entirely within Okta Workflows, without writing a single line of code (I suppose this is a lie if you consider JSON to be code). 

# Sounds neat! How do I do it?
For full details, see the [wiki](https://github.com/AnthonyBonarrigo/Jazz-Shrimp/wiki)
