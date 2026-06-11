# The markup rules

Keep FAQ markup valid and honest: the schema must match the visible content exactly, each question must have one answer, the markup must be syntactically correct, and it must describe genuine user-facing FAQs. Markup that matches real content and validates cleanly is markup that works.

## Match the visible content

The cardinal rule is that the questions and answers in the schema must match what visitors see on the page. Marking up content that is not visible, or that differs from what users see, violates the guidelines and can lead the engine to disregard or penalize the markup. The schema is a description of the real FAQ, so it must describe the real FAQ accurately. Keeping the markup and the visible content in sync is the first rule.

## Structure each pair correctly

Each entry pairs one question with its answer, structured so the engine can tell which answer belongs to which question. The question text and the answer text each have their place in the structure. Getting this pairing right is what lets the engine extract the question-answer relationship. A well-formed entry has a clear question and a clear answer associated with it, following the type's expected structure.

## Validate the syntax

The markup must be syntactically valid, because a malformed structure may be ignored entirely. JSON-LD has a precise format, and a small error, a missing bracket, a wrong field, can break the whole block. Running the markup through a structured-data validation tool catches these errors before they cost you. Valid syntax is non-negotiable, because invalid markup does not partially work; it tends not to work at all.

## Keep it honest

Beyond matching and validity, the markup must describe genuine, useful FAQ content, not content contrived to exploit the format. Honest markup of real Q&A content is what the guidelines reward; markup that games the format risks being disregarded or penalized. The rules around matching, structure, and validity all serve the underlying principle that the schema should faithfully and honestly represent real content that helps users. Honesty in what the markup describes is the rule the others support.
