# Objective-question authoring: masked expert comparison

Main case: introductory AI course. Supplement: team-development course. Each course has seven shared targets and one item per target from each of two authoring approaches: 28 questions total.

- index.html: neutral-ID expert review, three dimensions, four reviewer IDs, browser-local save and JSON export.
- questions.html: targets/questions/reference keys and global prompt transparency. Item-to-method mapping, previous method-specific traces and LLM scores are withheld from this release.

Same-model proposed-workflow diagnostics exist locally; comparative expert results are pending. Neutral numbering hides method labels, but response format remains visible. A new dataset version protects earlier browser records; old exports are not silently migrated.

Dataset: oq-blind28-3374dd5b8c75

Authoring code, raw teaching documents and private mapping are not uploaded. Historical commits may contain earlier demonstrations; reviewers should use the current form and avoid repository history until ratings are complete.

- prompts.html and prompt-protocol.json: exact global generation/evaluation instructions, settings, schemas and anonymised input templates. Comparative model scores and private mappings remain local during expert review.

Ratings are saved in the reviewer browser only. Reviewers must download a progress backup or completed ratings JSON and send the file to the study coordinator; there is no automatic collection backend. The form displays a local-only/not-sent notice, a backup-needed status, a permanent backup button and a final download/send reminder. Download initiation is not proof the file was saved by the browser. Existing item IDs, dataset version and stored ratings are retained.
