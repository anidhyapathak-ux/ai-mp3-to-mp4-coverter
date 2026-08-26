# AI MP3 → MP4

A small website that converts MP3 audio into MP4 video using FFmpeg and optionally transcribes the audio with OpenAI.

## Run locally
1. Install Node.js and FFmpeg.
2. Run `npm install`.
3. Copy `.env.example` to `.env` and set `OPENAI_API_KEY`.
4. Run `npm start`.
5. Open `http://localhost:3000`.

Keep the OpenAI API key on the server; never put it in browser JavaScript.
