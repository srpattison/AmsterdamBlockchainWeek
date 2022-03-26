---
####################
### INSTRUCTIONS ###
####################
# This file is a template to create new events. In order to use it, duplicate
# the whole folder (/template) as a new folder (I.E. /my-event-name) inside of
# the /events folder, using for the folder name _only_:
# - lowercase letters
# - hyphens/dashes (-) instead of spaces
# - alphanumeric characters ('a' to 'z', '0' to '9')
# and edit the README.md file inside that new folder just created.
#
# The name of the folder will be used on the URL. Example:
# https://amsterdamblockchainweek.org/my-event-name
#
# _Don't_ rename the new file (README.md), only edit its content.
# _Don't_ remove any text before the colons at the beginning of each line,
# only edit what is after the colon. Example:
# Don't remove the word nor colon on 'description:'
#
# Every line starting with a hash symbol (#) is a comment. It will be ignored
# and can be safely removed, including these instructions.
###############


###########
### SEO ###
###########
# The title of the page, displayed by the browser on the title of the window.
# Ideally this is the same as the name of the event.
title: Workshop on Incentive Mechanism Validation

# Description for this event. This will be rendered as a <meta> tag in the HTML,
# and displayed on the /events page. Keep it short.
# Linebreaks are ignored, but they _must_ start with two spaces.
description:
  An in-person workshop dedicated to the practical application of optimization, control theory, and reinforcement learning for the development and validation of Ethereum protocols.

#####################
### EVENT DETAILS ###
#####################
# The name of the event you're creating.
# Ideally this is the same as the title.
name: Workshop on Incentive Mechanism Validation

# There _needs_ to be one hyphen before each paragraph.
# Linebreaks are ignored, but they _must_ start with two spaces.
# Indentation is crucial:
# Two spaces before the hyphen, four spaces before the text. _No_ tabs allowed.
# Add or remove paragraphs as needed, but remember the hyphen before each entry.
synopsis:
  -
    Mechanism design is a branch of economics focused on creating incentives to encourage the adoption of behavior such that higher-level goals are achieved. Mechanism designers begin by applying reverse game theory to construct mathematical descriptions of incentives, actors, and game mechanics. How can a proposed mechanism be validated? In a simulation, agents modeled on heuristics or control theory can interact with a mechanism and provide first-order checks. Further, given sufficient compute resources, reinforcement learning can be used to obtain performant or adversarial agents that provide robust experimental validation.
  -
    This workshop will consist of short talks and tutorials focused on the roles of and interplay between optimization, control theory, and reinforcement learning in the mechanism design life cycle. Presenters are encouraged to share how they have used optimization, control theory, reinforcement learning, and related techniques to build or analyze real-world cryptoeconomic systems. Regardless of prior background, we want attendees to leave with intuition regarding which tools and approaches work well and in what situations. We also seek to identify open problems in Ethereum where the above-mentioned techniques can be applied.


# The date should be in the format year-month-day (ISO 8601).
# Example: 2018-02-28
date: 2022-04-18
# The date when the event ends. Can be left empty or set to the same day the
# event starts.
endDate: 2022-04-18

# Set the time in 24 hours format, surrounded by quotes.
# _Only_ the starting time!
# Example: '18:00'
time: '08:00'
# Time when the event ends. Can be left empty.
endTime: '12:00'

# The URL where to akquire the tickets. Can be left empty.
tickets: https://sites.google.com/semiotic.ai/wimv2022

# If the entrance is free, set zero (0) as the price
# If there is no info on the price or pricing is too complex to put here, leave it empty.
# _Don't_ write the currency symbol (Euro symbol will be used).
price:

# The name of the venue where the event will be held. Can be left empty.
venue: Hôtel Mövenpick Amsterdam City Centre

# The address to link to a Google map. Please test the address on Google Maps.
# Example: Skalitzer Strasse 85-86, 10997 Berlin, Germany
address: Amsterdam, Netherlands

# The category of the event. Valid options:
# - conference
# - event
# - hackathon
# - workshop
# - drink
# Use _only_ one, and don't capitalize.
category: workshop


#################
### SPEAKERS ####
#################
# There _needs_ to be one hyphen before each entry.
# Linebreaks are ignored, but they _must_ start with two spaces.
# Indentation is crucial:
# Two spaces before the hyphen, four spaces before the text. _No_ tabs allowed.
# Add or remove speakers as needed, but remember the hyphen before each entry.
speakers: []
# speakers:
#  -
    # # Required.
    #name: Nathan Sexer

    # # Can be left empty.
    #title: Title?

    # # Can be left empty.
    #company: Blockchainweek.fr

    # # The full URL, including http(s)://. Can be left empty.
    #companyURL: https://ethcc.io/

    # # Just the twitter handle, without Twitter's URL, nor the '@' symbol.
    # # Can be left empty.
    #twitter: nathansexer

    # # The full URL, including http(s)://. Can be left empty.
    #website: https://blockchainweek.fr

    # # The bio is a single line.
    # # Linebreaks are ignored, but they _must_ start with two spaces.
    #bio: Hi.
    #   This is Nathan.
    #name: See all events
    #title: President
    #company: HERE
    #companyURL: https://devconnect.org/schedule
    #twitter: efdevconnect
    #website: https://jdetychey.com
    #bio: Jerome De Tychey is Jerome,
    #  known as Jerome, he co-founded Asseth and leads Asseth with other asseths.

### DON'T MAKE CHANGES BELOW THIS LINE! ###
---
<!-- ### DON'T MAKE CHANGES BELOW THIS LINE! ### -->

<Event-Content/>
