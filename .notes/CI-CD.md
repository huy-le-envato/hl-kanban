# CI-CD

all deployment related lives in github actions
app owners works with claude overtime creates environment drifts.
it happed with one of the app, i believe it was brandlens.
where the production app was missing pdftotext and ffmpeg. local has these binaries managed by homebrew.
the solution is to put in our ai-ops agent harness an memory to ensure app dev is done in a kamal deploy destination.
kamal destination could be *local*. or even *staging* if we have single person team. 
