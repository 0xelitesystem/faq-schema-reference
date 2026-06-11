# What it is

FAQ schema is structured data that marks up a list of questions and their answers on a page, using a standard vocabulary so search engines and AI systems recognize the content as question-and-answer pairs. It is typically written in JSON-LD and describes the FAQ content that already exists on the page.

## Structured data, briefly

Structured data is a standardized way of labeling content so machines understand what it is, not just what it says. Instead of leaving an engine to infer that a block of text is a question and another is its answer, structured data states it explicitly in a vocabulary the engine knows. FAQ schema is the part of that vocabulary for question-and-answer content, telling machines this is a question and this is its answer.

## The FAQPage type

The relevant type is FAQPage, which describes a page containing a list of frequently asked questions, each paired with its answer. Within it, each question and its answer are labeled distinctly. This structure lets an engine extract the individual question-answer pairs and understand the relationship between them. The type exists precisely to capture the common pattern of a page that poses questions and answers them.

## Written in JSON-LD

FAQ schema is commonly written in JSON-LD, a format that places the structured data in a script block in the page rather than woven through the visible HTML. This keeps the markup separate from the content's presentation, making it easier to add and maintain. The JSON-LD describes the same questions and answers the reader sees, in the machine-readable form the engine reads. The reader sees the FAQ; the engine reads the JSON-LD describing it.

## It describes, it does not replace

A key principle is that FAQ schema describes content that genuinely exists on the page for users; it does not stand in for it. The markup and the visible content should match: the questions and answers in the schema are the ones a visitor actually sees. Schema is a layer of explanation on top of real content, not a hidden set of questions invented for machines. The visible FAQ is the thing; the schema makes it legible.
