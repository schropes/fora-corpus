# Fora Corpus

This repository contains information about the Fora corpus, including a description of the data, information about requesting access, starter code, and models for processing the data.

The corpus is described in the ACL 2024 paper "Fora: A corpus and framework for the study of facilitated dialogue" by Hope Schroeder, Deb Roy, and Jad Kabbara. The ACL anthology paper link is [here](https://aclanthology.org/2024.acl-long.754/).

<br>

## The corpus

This dataset includes 262 transcribed small group conversations over 39,000+ speaker turns.
Conversations come from 16 unique conversation collections. Each collection was a conversation series hosted in partnership between [Cortico](https://cortico.ai/), a national non-profit, and one or more organizations. 

Collections in the corpus are wide-ranging in the conversation purpose and topics covered. Collections include conversations about city manager selection, resourcing challenges in NYC during COVID-19, and challenges to Maine school districts.
Extended collection descriptions and any public links to additional information are publicly available in this [sheet.](https://github.com/schropes/fora-corpus/blob/main/Fora%20corpus%20-%20collection%20information.csv)

Beyond publicly available collection-level information in this [sheet](https://github.com/schropes/fora-corpus/blob/main/Fora%20corpus%20-%20collection%20information.csv), the Fora corpus includes transcribed speaker turns for every conversation in the corpus, annotations for a 25% sample of the conversations, and an example conversation guide for each conversation collection. These resources are provided through an access agreement for use in research, described in a later section.

<br>

## Annotations: personal sharing and facilitation strategies

Over 25% of the conversations (70 conversations, 10,625 speaker turns) have been manually annotated for two types of personal sharing, and seven defined facilitation strategies.

All annotations allowed for multi-labeling.

All conversation turns were annotated for participant sharing. 

### Personal sharing
1. __Personal story:__
A personal story describes a specific series of events that happened in the speaker's life. Usually, this story happened in the past, but it may be happening in the present. Stories can be as short as one sentence.
Examples:
* `I rode my bike all across town until I found that darn hospital!`
* `10 years ago, I went to the coroner's office after my brother passed away. They would not help me find out what happened.`
2. __Personal experience:__
A mention of personal experience includes the mention of of professional background, or general statements about the speaker's life that are *not* a sequence of specific events, unlike stories described above.
Examples:
* `I get mistaken for a lot of other Asian people in my sorority or in other sororities.` (This describes a recurring experience, so it's not a story but it is a personal experience.)
* `My name is Justyce, I am a student at UW Madison, and I'm a senior.` (This shares background information about the speaker that relates to their personal identity, but is not a story.)


### Facilitation strategies

Facilitator turns were annotated for facilitation strategies defined here.

__Validation Strategies__

1. __Express appreciation:__
* `Thanks for sharing that.`
* `Alright, great, now do I have everyone? Appreciated. Sure. Let’s move on.`
2. __Express agreement or affirmation:__
* `Definitely. I hear you.`
* `I agree. I keep hearing that in these conversations.`


__Invitations to Participate__

1. __Open invitation:__ to participants to partic-
ipate
* `Alright with that being said, does anyone want to kick us off?`
* `Ok great. Now anyone who wants to go next can unmute.`
2. __Specific invitation__ to participate, ad-
dressed to a particular speaker
* `Kelly? Did you want to go next?`
* `Great. That’s all I wanted to put on the table. Oh, Joe? I see you’re raising your hand. Are you ready to go?`

__Facilitation Strategies__

1. __Model examples:__ facilitator models an example answer to the question or prompt
* `So first we are going to give introductions and then share a value that’s important to us. I’ll kick us off. I’m Kelly and a value that’s important to me is courage.`
* `Sharing stories is what we’re doing next. Some people are confused in this stage so I’ll give you an example. My grandmother lived next door to us when I was growing up. One time, the sheriff came by, and I was playing outside. It scared me to see this guy, an unknown man, come to our house when we lived that far out in the country. And my grandmother’s attitude towards him didn’t help. Since then I’ve been scared of the police. Ok does anyone want to share your first encounter with police next?`

2. __Follow-up question:__ facilitator addresses a follow-up question to a speaker already speaking
* `Wow, Kelly, that’s such a touching story. Did you ever find out who sent the package?`

3. __Make connections:__ facilitator includes a statement making a connection to or between different participants in the conversation, or across topics in the conversation
* `That’s similar to what Jamie shared earlier, right?`
* `I have a similar experience that resonates.`
* `That connects to what we were discussing earlier.`

A codebook and examples for each type of sharing and facilitator sharing strategy is included in this repository.

<br>

## Fora Corpus Access

Access will be managed through an agreement with the [MIT Center for Constructive Communication](https://www.ccc.mit.edu/). Access requests are managed through [this](https://docs.google.com/forms/d/e/1FAIpQLSf3o8RqPcE_cxcvQ5Zfm5MC4KrlSa3JHxtYrUFZb5FjkLMEBg/viewform?usp=sf_link) form, and we will aim to handle access requests within a week. 
Access is subject to the terms outlined in this [license](https://github.com/schropes/fora-corpus/blob/main/Fora%20Corpus-license.txt), which is based on the Responsible AI License ([RAIL](https://www.licenses.ai/rail-license-generator)).

<br>


## Questions

Please open an issue or contact Hope Schroeder with any questions.
