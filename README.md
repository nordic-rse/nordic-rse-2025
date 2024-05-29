# Nordic RSE Conference 2025

Nordic Research Software conference 2025 website and planning.


You can preview the site locally using
[Zola](https://www.getzola.org/documentation/getting-started/overview/):

```
$ zola serve
```


## The Issues I Wanted to Fix

 - **Hidden conversations**
   A lot of the planning for this conference happened in meetings. For a new volunteer or a participant, it's hard to gain ownership in the conference.

   Later we moved to Zulip and to coffee breaks. These are more accessible, but still not as public as I would like.

 - **Missed decisions**
   We often made decisions in a meeting and forgot. We then had to go through the same conversation again. I want to clarify what counts as a decitions and make sure they are written down.
  
 - **Forgotten tasks**
   Some things happened late or did not happen because no-one was assigned to do it.


## How this repository works

This is a suggestion, we can change this as we go.

My idea is to follow a single endorsement policy:
 1. Anyone can make a suggestion (formally by a pull request)
 2. Any conference organizer can merge (and should, if they approve)
 3. Organizers should not merge their own requests.

- Discussions happen publicly in issues.
- When there is an actual task to do, this should be a new issue and should be assigned. Tasks that are not assigned to a single person tend to not be done.
- Information in this repository is official and nothing outside this repository is official.
- There are few things that cannot be public. For example communication with invited speakers, who
  have not yet accepted. This information is added when possible.


### The Website

The contents of the website are stored in `content/`. If you want to edit
the website, this is usually what you are looking for. The main page is
in `_index.md`.

The `static` and `templates` folders are also related to building the website.


### Documents

Other planning documents are stored in the `documents` folder. These don't
appear on the website.

These include for example email templates, social media messages and meeting minutes.
