# gemini-wordle-clone
Wordle clone generated with Gemini Canvas in two prompts

## Important
The app ran successfully in Gemini Canvas, but fails here. The reason is that Gemini implemented a call to Gemini :) to perform the word validity check and that call requires an API Key when run outside of the Gemini environment. In the code you'll see the apiKey var set to an empty string.
