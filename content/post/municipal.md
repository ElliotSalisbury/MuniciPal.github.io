+++
title = 'Munici-Pal'
date = 2024-04-24T22:32:51-07:00
draft = false
+++

## Munici-Pal

I developed a tool to help citizens keep informed with the weekly ongoings of their town's council meetings.

See an example of this platform deployed on my hometown, Squamish:
[Munici-Pal: Squamish](https://squamishdemocracy.ca)

### Methodology

* Web scraping to pull each council meeting's video and agenda.
* Uses Speech to Text Transcription models
* Speaker Diarization to understand which person said which parts of the transcript.
* Dynamic Programming to align the transcript with the given Agenda
* LLM's to summarize what was discussed and voted on for each item on the agenda.
* RAG to enable the users to find information and ask questions about their town.
