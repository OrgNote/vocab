# OrgNote Vocabulary

## Phases

1. Brain Dump
2. Organize
3. Clarity
4. Focus
5. Feedback Loop

## Phase 1 - Brain Dump

**Classes**

- Person
- Note
- Device
  - TODO multiple browser on same device?

**Rels**

- created (Person, Note)
- createdAt (Note, _datetime_)
- createdWith (Note, Device)

### Versioning

- Person thoughtOf Idea
- Idea notedAt _datetime_
- Note of Idea
- Note createdAt _datetime_
- Note createdWith Device
- Note contains _text_


## Phase 2 - Organize

**Classes**

- Person

- Idea
- Expression
- Note
- Notebook

- Device
- App

**Rels**

- Person has Idea
- Idea guid _text_
- Expression of Idea
- Expression contains _text_
- Expression createdAt _datetime_
- Expression createdOn Device
- Expression createdWith App
  - TODO how to track browser?
- Expression a Note|Notebook
