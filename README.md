# Phonemix (foʊnimɪks)
Phonemix is a voice cloning repo designed to improve quality by using a phoneme based tokenizer.
# Why use phonemes instead of a standard tokenizer?
The fundamental idea behind using phonemes is that instead of needing to train a model to speak thousands of tokens (and millions of combinations of tokens), the model wil only need to learn how to speak 44 phonemes, or 1936 combinations of phonemes. This should *THEORETICALLY* lead to faster training times, faster finetuning, and better quality with limited samples.
# Suggested Input Clips
Unlike other models, you shouldn't need hours, or even minutes, of samples to get good sounding results. A priority should be making sure your samples contain every spoken english phoneme, if possible.

If you have the ability to control the sample(s), a good starting place is the following sentence, which contains all English phonemes:

"That quick beige fox jumped in the air over each thin dog. Look out, I shout, for he's foiled you again, creating chaos."

EN-US: ðæt kwɪk beɪʒ fɑks ʤʌmpt ɪn ði ɛr ˈoʊvər iʧ θɪn dɔɡ. lʊk aʊt, aɪ ʃaʊt, fɔr hiz fɔɪld ju əˈɡɛn, kriˈeɪtɪŋ ˈkeɪɑs.

EN-UK: ðæt kwɪk beɪʒ fɒks ʤʌmpt ɪn ði eər ˈəʊvər iːʧ θɪn dɒɡ. lʊk aʊt, aɪ ʃaʊt, fɔː hiːz fɔɪld juː əˈɡɛn, kriˈeɪtɪŋ ˈkeɪɒs.

# Accent Problems
As you might have caught in the above section, a minor inconvience when dealing with phonemes is that not everyone reads the same words as teh same phonemes. As the example above points out, most US speakers pronounce air as "ɛr", and most UK speakers pronounce air as "eər". People are also just different, I pronounce bag as "bɛɡ" instead of the more common "bæɡ". While phonemes can give you more control over what the speaker is saying, it can be a little bit more work to get the input right.

# Additional Notes
If you've stumbled across this repo before the initial commit and are interested in learning more, here are some websites that can help you get used to the English phonemes.

Convert regular text to phonemes https://tophonetics.com/

Phoneme Lists (with examples)

https://magoosh.com/english-speaking/44-phonemes-in-english-and-other-sound-blends/

https://www.readingrockets.org/sites/default/files/migrated/the-44-phonemes-of-english.pdf
