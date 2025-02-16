## Inspiration
We are two passionate Pink Floyd fans who realized that much of their music does not have accompanying visualizers or music videos. Inspired by the band’s immersive soundscapes and abstract storytelling, we set out to create an AI-driven tool that generates synchronized visuals for any song. We wanted to bring music to life in a way that enhances its emotional and thematic depth, making every listening experience more immersive.

## What it does
Resonance is an AI-powered music video generator that transforms any song into a stunning, synchronized visual experience. By analyzing a song’s tempo, mood, and lyrics, it creates dynamic, 2D animated sequences that seamlessly match the music’s emotional tone. The visuals range from abstract and surreal animations to minimalist storytelling, ensuring that every generated video uniquely complements the song it accompanies.

## How we built it
We built Resonance using AI-powered audio analysis, NLP for lyric interpretation, and Stable Diffusion for visual generation.
- **Audio Processing with Librosa:** Extracted tempo, pitch, energy, and brightness from the MP3 file to determine the song’s mood and dynamics.
- **Lyric Analysis with OpenAI API:** Used NLP to analyze sentiment, themes, and imagery in the lyrics.
- **Prompt Generation:** Combined audio and lyric insights to generate structured text prompts describing visual scenes that match the song’s emotions.
- **Animation with AnimateDiff-Lightning:** Used Stable Diffusion to create short animated clips based on the prompts, maintaining a hand-drawn, abstract aesthetic.
- **Video Assembly:** Merged AI-generated clips using FFmpeg and OpenCV, ensuring smooth transitions in sync with the song.

## Challenges we ran into
- Synchronizing visuals with music: Ensuring that AI-generated visuals match beats, mood shifts, and lyric changes was a major challenge.
- Maintaining artistic consistency: AI-generated images often vary in style, so we had to refine our pipeline to create a cohesive visual narrative.
- Computational costs: Generating high-quality, frame-by-frame AI animations is resource-intensive, requiring optimization for speed and efficiency.

## Accomplishments that we're proud of
- Successfully generating music videos that feel emotionally and thematically connected to the songs.
- Developing a system that allows users to upload any song and get a completely unique, AI-generated video.
- Overcoming the technical challenges of real-time music analysis and animation generation.
- Creating a tool that can bring new life to classic songs, especially ones that never had official music videos.

## What we learned
- How to fine-tune AI models to generate more controlled and meaningful outputs.
- The importance of balancing automation with artistic intent when working with generative AI.
- Advanced techniques for analyzing and extracting emotional characteristics from music.
- Optimizing AI-generated video rendering to improve speed and efficiency.

## What's next for Resonance
- Expanding style options: Allowing users to select different artistic styles, from hand-drawn to cinematic.
- Real-time generation: Optimizing performance to enable near-instant video generation.
- Customization features: Letting users tweak visual themes, colors, and pacing to match their creative vision.
- Multi-song storytelling: Creating visual narratives that span entire albums or playlists.
- Bringing it to more artists: Partnering with musicians to create AI-assisted music videos for their work.
