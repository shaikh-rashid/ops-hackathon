# OPS Hackathon: Archive team problem definition notes
January 29th, 2019

## Domain knowledge
Record series are developed when there is a good reason for them to be developed - they hold relevance, relevant to Ontarios history, 
- Archives team decide why certain topics are important, and then find it
- Rank documents based on relevance? Fei - that’s crazy

Want people to access archives database
- Go to ‘Advance search options’

An office/business creates documents (for a specific business reason). At some point, the documents are sent to the archives to be stored. 
- Researchers would like to know what that business did, without 

Organize it in different ways:
1. Context - Where did they come from, which office which ministry, why create them, who created them, which other ministries use them
2. Certain ministry creates different sets of documents - Meeting minutes, policies, drug program, directors office records but all these relate to the ministry of health
3. Groups of records
4. Item level

Records are usually one to one. A record can contain multiple files/items.
Record - anything that is in a fixed format. Voicemail, cassette. It can be a collection or a single item.

F 4622 - Nelson Mandela Children’s Fund - unique identifier for a group of records
Title, date, description, doc, pdf, audio

Description: What information is within this group, what is in it, gives you the context, a description of the records <—— Humans write this
Creator - a separate database containing creator authorities

Every record is divided in to series - each series id is associated with its parent - essentially a subset. Can go all the way to a single item.

Scope property of a series is the hardest to determine, done by humans

Problem: Getting terabytes of data pouring in
- A need to protect individual’s person details - kids, sickness, lots of exemptions

## Potential problems to solve
1. Relevant or irrelevant for archives
2. A lot of energy going into scope and label - automate it, suggest
3. Retrieval - researchers want to find why a politician did a certain action e.g. ‘why did the wynn government …’
4. Need to exempt certain materials
5. Collection of digital photos
    - Go through every single photo
    - See what it is
    - Sometimes you can’t do that —  too many photos, cannot verify manually, some series
    - Filter out or note poorly tagged things, incorrectly tagged things

## Developing the problem statement

Tags - terms or phrases
	geographic names, subject names, terms

Determine if the document is actually what the collaborator says it is

**Bottom line problem:** Tagging on content and file name for search

Solutions:
- What the model thinks is the most important keywords
- Deep learning - not possible, training takes too long
- Validate the tagging of a series (photos, text)
- Don’t do images - too hard to define the object (cathleen wynn or random woman?), sticking to text
- We have access to a validation set - a group of human generated tags
