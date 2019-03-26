# GCPS Team Messaging options analysis

<aside class="notice">
This document is a work in progress and should not be considered accurate information
</aside>

This document is not currently in its final state, and shouold be considered a work in progress

</div>
</div>


## Summary


|        Product        | Does it meet our MVP needs? | Reasons |
|:---------------------:|:---------------------------:|:-------:|
|         Slack         |             TBD             |   TBD   |
|   Slack Enterprise    |             TBD             |   TBD   |
|   Rocket.chat Cloud   |             TBD             |   TBD   |
|    Microsoft Teams    |             TBD             |   TBD   |
|     Cisco Jabber      |             No              |         |
|   Cisco Webex Teams   |             TBD             |         |
| Blackberry Enterprise |             No              |         |
|      Mattermost       |             TBD             |   TBD   |

### Goals

We beleive that a modern Group Instant Messaging tools will help to reduce hurdles for the following objectives:
* Improve sector wide transparent and communication
* Improve collaboration across physical locations, as well as across horizontal services, programs, and teams
* Create a centralized platform to publish important information that integrates with exist workflows

We expect that by aiming to improve on these objectives we will create a more efficient, transparent and happier workplace within the GCPS sector.

If at the end of the experiment we have high levels of adoption, we will expand our uses to focus on collaborating externally with DSB and client departments, so priority will be given to a tool that can scale et future needs.

### Options being considered

#### Slack  

* Free
* Direct signup via Slack.com, owned and managed by GCPS 


#### Slack Enterprise
* Cost TBD
* Direct signup via Slack.com, owned and managed by GCPS 

#### Rocket.chat Cloud   
* $40-$20 USD per user, Annually
* Direct signup via Slack.com, owned and managed by GCPS  
                                                                |
#### Microsoft Teams  
* Free to GCPS, because paid by TSS/SSC?
* I beleive SSC has licenses for Microsoft Teams available as part of the Office 365 procurement. We would propose to be given the licenses for GCPS employees from \[TSS/SSC/EA?\] for a sector wide adoption    

#### Cisco Jabber
* Free to GCPS, because part of an SSC Pilot.
* Licenses managed by TSS

#### Cisco Teams
* TBD
* TBD

#### <del>Blackberry Enterprise </del>
* <del> Cost TBD </del>
* Blackberry enterprise no longer being considered, as it is no longer a pilot being run by SSC. Replaced by Cisco Jabber

####  Mattermost
* TBD, in partnership with BPS - Productivity Tools Team
* Product, and licenses to be managed by BPS Productivity Tools Team


## Key Features - Must have for MVP

### Basics 

|              Product              | Direct Msg | Group Msg | Public Channels | Private Channels | Custom Notification |   Data Retention   | Searchable  History | Portable Windows App* | Managed Desktop App* |
|:---------------------------------:|:----------:|:---------:|:---------------:|:----------------:|:-------------------:|:------------------:|:-------------------:|:---------------------:|:--------------------:|
|          Slack for Teams          |     X      |     X     |        X        |        X         |          X          | Up to 10k messages |          X          |           X           |                      |
|         Slack Enterprise          |     X      |     X     |        X        |        X         |          X          | Fully customizable |          X          |           X           |                      |
|         Rocket.chat Cloud         |     X      |     X     |        X        |        X         |          X          |                    |                     |           X           |                      |
|          Microsoft Teams          |     X      |     X     |        X        |        X         |                     |                    |          X          |                       |                      |
|           Cisco Jabber            |     X      |     X     |                 |                  |                     |                    |                     |                       |                      |
|            Cisco Teams            |     X      |     X     |                 |                  |                     |                    |                     |                       |                      |
| <del> Blackberry Enterprise</del> |            |           |                 |                  |                     |                    |                     |                       |                      |
|            Mattermost             |     X      |     X     |        X        |        X         |          X          |                    |          X          |                       |                      |

 \* In order to reduce time to deployment, MVP option must already be packaged and ready to install via request to TSS/SSC? or have a portable version available that does not require admin rights to install

### Platforms

|              Product               |   Desktop    |   Android    |    Apple     |   Browser    |
|:----------------------------------:|:------------:|:------------:|:------------:|:------------:|
|               Slack                |      X       |      X       |      X       |      X       |
|          Slack Enterprise          |      X       |      X       |      X       |      X       |
|            Rocket.chat             |      X       |      X       |      X       |      X       |
|          Microsoft Teams           |      X       |      X       |      X       |      X       |
|            Cisco Jabber            |      X       |      X       |      X       |              |
|            Cisco Teams             |      X       |      X       |      X       |              |
| <del> Blackberry Enterprise </del> | <del>X</del> | <del>X</del> | <del>X</del> | <del>X</del> |
|             Mattermost             |      X       |      X       |              |      X       |

###  Integration and Interoperability

The ability for a messaging tool to integrate into users regular workflow is a huge benefit to user adoption. The following identified integrations are not all mandatory, but will be a large factor in selecting the appropraite tool for the type of work we do in GCPS

#### Global

|             Product              | Outlook Calendar | OpenText | Dynamics | Sharepoint | JIRA** | Confluence** |
|:--------------------------------:|:----------------:|:--------:|:--------:|:----------:|:------:|:------------:|
|             Slack *              |                  |          |          |            |   X    |      X       |
|         Slack Enterprise         |                  |    \*    |    \*    |     X      |   X    |      X       |
|        Rocket.chat Cloud         |                  |    \*    |    \*    |     \*     |   X    |              |
|         Microsoft Teams          |                  |          |          |            |   X    |              |
|           Cisco Jabber           |                  |          |          |            |        |              |
|           Cisco Teams            |                  |          |          |            |        |              |
| <del>Blackberry Enterprise</del> |                  |          |          |            |        |              |
|            Mattermost            |        X         |    X     |          |            |        |              |

 \* Indicates that no current integration exists, however the are options to develop these integrations in the future through the use of APIs
 \*\*  X indicates that an integration option for the project exist,  but it may not integrate immediately with our on-prem tools as it may violate security restrictions to open flows between the tools.

#### Development Teams (not just developers, full team)

|             Product              | GitLab** | BitBucket** | Azure DevOps** | GitHub |
|:--------------------------------:|:--------:|:-----------:|:--------------:|:------:|
|             Slack *              |    X     |             |                |   X    |
|         Slack Enterprise         |    X     |      X      |                |   X    |
|        Rocket.chat Cloud         |    X     |      X      |     Alerts     |   X    |
|         Microsoft Teams          |    X     |             |                |   X    |
|           Cisco Jabber           |          |             |                |        |
|           Cisco Teams            |          |             |                |        |
| <del>Blackberry Enterprise</del> |          |             |                |        |
|            Mattermost            |    X     |      X      |                |        |

 \* maximum of 10 integrations available with the free version of Slack
 \*\*  X indicates that an integration option for the project exist,  but it may not integrate immediately with our on-prem tools as it may violate security restrictions to open flows between the tools.

#### Managers

#### Directors

#### Misc


## Additional Features (nice to have)

These are features that have been indentified as nice to have, in order to improve the user experience and get the most out of the slected tool

### Collaboration

|             Product              | Voice Calls | Video Conference | Screen Sharing | File Sharing | Drag & Drop | Whiteboard | Tagging/@Mentions |
|:--------------------------------:|:-----------:|:----------------:|:--------------:|:------------:|:-----------:|:----------:|:-----------------:|
|              Slack               |      X      |        X         |                |      X       |      X      | 3rd Party  |         X         |
|         Slack Enterprise         |      X      |        X         |       X        |      X       |      X      | 3rd Party  |         X         |
|        Rocket.chat Cloud         |      X      |        X         |       X        |      X       |             |            |         X         |
|         Microsoft Teams          |      X      |        X         |       X        |      X       |             |            |         X         |
|           Cisco Jabber           |    WebEx    |      WebEx       |       X        |      X       |      X      |            |                   |
|           Cisco Teams            |    WebEx    |      WebEx       |       X        |      X       |      X      |            |                   |
| <del>Blackberry Enterprise</del> |             |                  |                |              |             |            |                   |
|    Mattermost Enterprise E20     |      X      |        X         |       X        |              |             |            |                   |


### User Experience

|             Product              | Emoji Reactions | Message Threading | Bots/Scheduled Messages | Searchable File Contents |
|:--------------------------------:|:---------------:|:-----------------:|:-----------------------:|:------------------------:|
|              Slack               |        X        |         X         |            X            |            X             |
|         Slack Enterprise         |        X        |         X         |            X            |            X             |
|        Rocket.chat Cloud         |        X        |         X         |            X            |                          |
|         Microsoft Teams          |                 |         X         |            X            |            X             |
|           Cisco Jabber           |                 |                   |                         |                          |
|           Cisco Teams            |                 |                   |                         |                          |
| <del>Blackberry Enterprise</del> |                 |                   |                         |                          |
|            Mattermost            |        X        |         X         |            X            |                          |




### Data 

#### Access and Member Management 

|             Product              | Single-Channel Guests | Multi-Channel Guests | Shared Workspace Channels | Single Sign-on (See SSO Options) | User Groups |
|:--------------------------------:|:---------------------:|:--------------------:|:-------------------------:|:--------------------------------:|:-----------:|
|              Slack               |                       |                      |                           |                                  |             |
|         Slack Enterprise         |           X           |          X           |             X             |                X                 |      X      |
|        Rocket.chat Cloud         |                       |                      |                           |                                  |             |
|         Microsoft Teams          |                       |                      |                           |                                  |             |
|           Cisco Jabber           |                       |                      |                           |                                  |             |
|           Cisco Teams            |                       |                      |                           |                                  |             |
| <del>Blackberry Enterprise</del> |                       |                      |                           |                                  |             |
|            Mattermost            |                       |                      |                           |                                  |             |

#### SSO Options

|              Product              | ADFS | Auth0 | G Suite | Last Pass | MS Azure |
|:---------------------------------:|:----:|:-----:|:-------:|:---------:|:--------:|
|               Slack               |      |       |         |           |          |
|         Slack Enterprise          |  X   |   X   |    X    |     X     |    X     |
|         Rocket.chat Cloud         |  X   |       |         |           |          |
|          Microsoft Teams          |      |       |         |           |          |
|           Cisco Jabber            |      |       |         |           |          |
|            Cisco Teams            |      |       |         |           |          |
| <del>Blackberry Enterprise </del> |      |       |         |           |          |
|            Mattermost             |      |       |         |           |          |



