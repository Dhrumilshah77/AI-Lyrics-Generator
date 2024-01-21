# AILyricsGenerator

#### Work in Progress
##### Using data from [Kaggle on Genius Dataset](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information) to build a model that generates lyrics.

![image](https://github.com/Dhrumilshah77/AI-Lyrics-Generator/assets/67861872/7d770410-d5b9-489d-b5d2-622885b64c11)

Project Motivation
Recognizing the various AI-driven text generation models and their contributions.
Emphasizing the unique dimension added by focusing on artist-specific lyric generation, bridging the gap between technology and artistry.
Acknowledgment of the existing AI-driven text generation models and the need for a more artist-specific approach.
Expressing the project's goal of offering a tool that aids songwriters and serves as a source of inspiration for new and aspiring artists.


Embedding Layer: Convert characters into numerical vectors for effective information representation.
Gated Recurrent Unit (GRU) Layer: Capture dependencies within lyrics, addressing the vanishing gradient problem.
Dense Layer: Process GRU outputs for final abstraction and logits generation


Evaluation
Employ quantitative metrics like Bleu Score with the chencherry.method1..
Bleu1 Score: 0.004
Metrics derived from a previous paper was used to get the Lyrics Quality Score, Rhyme Density Score and Sentiment Score
Lyrics Quality Score:
Rhyme Density Score:
Sentiment Score


Conclusion and Future Scope
Demonstrated promising results with RNN in artist-specific lyric generation.
Successful capture of intricate nuances, including vocabulary, rhyme schemes, and thematic elements.
Generated lyrics exhibit coherence and authenticity, resembling distinctive artist traits.
Project highlights the power of machine learning in natural language processing for music creativity.
Future directions include lyric customization, genre experimentation, and audio synthesis from lyrics.

