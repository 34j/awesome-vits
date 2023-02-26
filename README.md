# List of repositories relevant to VITS

The author does not understand anything about machine learning and this text may contain many errors.
If the code is publicly available, the Github link shall be attached.
I am sure there are many more great repositories not listed here. Sorry I didn't have time.

## Original

- [jaywalnut310/vits: VITS: Conditional Variational Autoencoder with Adversarial Learning for End\-to\-End Text\-to\-Speech](https://github.com/jaywalnut310/vits)

## Modified

### SoftVC

Replacing `VITS`' `TextEncoder` with [`HuBERT`](https://github.com/bshall/hubert)'s `ContentEncoder`
eliminates the need for inputting phoneme sequences (i.e., eliminate language dependence).
`HuBERT` is part of [`SoftVC`](https://github.com/bshall/soft-vc).

- [innnky/so\-vits\-svc: 基于vits与softvc的歌声音色转换模型](https://github.com/innnky/so-vits-svc)
- [quickvc/QuickVC\-VoiceConversion: QuickVC: Any\-to\-many Voice Conversion Using Inverse Short\-time Fourier Transform for Faster Conversion](https://github.com/quickvc/QuickVC-VoiceConversion)
- [CjangCjengh/MoeGoe: Executable file for VITS inference](https://github.com/CjangCjengh/MoeGoe) (SoftVC/W2V2)
- [PlayVoice/VI\-SVC: vits singing voice conversion based on ppg & hubert；singing voice clone;](https://github.com/PlayVoice/VI-SVC)
- [Francis\-Komizu/Sovits: An implementation of the combination of Soft\-VC and VITS](https://github.com/Francis-Komizu/Sovits) Deprecated
- [vtuber\-plan/vcvits: Non Parallel Voice Conversion based on VITS](https://github.com/vtuber-plan/vcvits)

### iSTFT (inverse short-time Fourier transform)

Performance is improved by improving the decoder, which was the bottleneck, with multiband generation and inverse short-time Fourier transform.

- [quickvc/QuickVC\-VoiceConversion: QuickVC: Any\-to\-many Voice Conversion Using Inverse Short\-time Fourier Transform for Faster Conversion](https://github.com/quickvc/QuickVC-VoiceConversion)
- [MasayaKawamura/MB\-iSTFT\-VITS: Lightweight and High\-Fidelity End\-to\-End Text\-to\-Speech with Multi\-Band Generation and Inverse Short\-Time Fourier Transform](https://github.com/MasayaKawamura/MB-iSTFT-VITS)
- [hcy71o/MB\-iSTFT\-VITS\-with\-AutoVocoder: Incorporating AutoVocoder to MB\-iSTFT\-VITS](https://github.com/hcy71o/MB-iSTFT-VITS-with-AutoVocoder)
- [\[2206\.00208\] AdaVITS: Tiny VITS for Low Computing Resource Speaker Adaptation](https://arxiv.org/abs/2206.00208)

### Other Improvements

- [innnky/vispeech: 基于vits fastspeech2 visinger的tts模型](https://github.com/innnky/vispeech)
- [CODEJIN/VITS\_Diffusion](https://github.com/CODEJIN/VITS_Diffusion)
- [hcy71o/SC\-VITS: VITS\-based zero\-shot TTS system varying with diverse style/speaker conditioning methods\.](https://github.com/hcy71o/SC-VITS)
- [innnky/emotional\-vits: 无需情感标注的情感可控语音合成模型，基于VITS](https://github.com/innnky/emotional-vits)
- [OlaWod/FreeVC: FreeVC: Towards High\-Quality Text\-Free One\-Shot Voice Conversion](https://github.com/OlaWod/FreeVC)
- [Edresson/YourTTS: YourTTS: Towards Zero\-Shot Multi\-Speaker TTS and Zero\-Shot Voice Conversion for everyone](https://github.com/Edresson/YourTTS) Zero-shot voice conversion which developed earlier.

### Other Languages

- [Francis\-Komizu/VITS: ACG Text\-to\-Speech](https://github.com/Francis-Komizu/VITS)
- [Francis\-Komizu/VITS\-Bilingual: Chinese\-Japanese Bilingual Text\-to\-Speech](https://github.com/Francis-Komizu/VITS-Bilingual)
- [hcy71o/SC\-VITS: VITS\-based zero\-shot TTS system varying with diverse style/speaker conditioning methods\.](https://github.com/hcy71o/SC-VITS)
- [rotten\-work/vits\-mandarin\-windows: VITS for Mandarin\. Support Windows and Linux, low\-end and high\-end hardwares](https://github.com/rotten-work/vits-mandarin-windows)
- [AlexandaJerry/vits\-mandarin\-biaobei: application of vits on mandarin tts](https://github.com/AlexandaJerry/vits-mandarin-biaobei)
- [CjangCjengh/vits: VITS implementation of Japanese, Chinese, Korean, Sanskrit and Thai](https://github.com/CjangCjengh/vits)
- [isletennos/MMVC\_Trainer: AIを使ったリアルタイムボイスチェンジャー\(Trainer\)](https://github.com/isletennos/MMVC_Trainer)
- [\[2211\.09365\] Low\-Resource Mongolian Speech Synthesis Based on Automatic Prosody Annotation](https://arxiv.org/abs/2211.09365)
- [Period VITS](https://arxiv.org/abs/2210.15964)

## Refactored

Because refactoring takes time, the latest technologies are not always adopted in theses repositories. However, these should be made easier to use.

- [coqui\-ai/TTS: 🐸💬 \- a deep learning toolkit for Text\-to\-Speech, battle\-tested in research and production](https://github.com/coqui-ai/TTS)
- [espnet/espnet: End\-to\-End Speech Processing Toolkit](https://github.com/espnet/espnet)

## Others

### GUIs and pre-trained models

- [CjangCjengh/MoeGoe\_GUI: GUI for MoeGoe](https://github.com/CjangCjengh/MoeGoe_GUI)
- [Francis\-Komizu/StellaVoiceChanger: Deep\-learning\-based voice changer, supporting local inference\.](https://github.com/Francis-Komizu/StellaVoiceChanger)
- [luoyily/MoeTTS: Speech synthesis model /inference GUI repo for galgame characters based on Tacotron2, Hifigan, VITS and Diff\-svc](https://github.com/luoyily/MoeTTS)
- [TheKOG/Gal\-Voice\-Bot](https://github.com/TheKOG/Gal-Voice-Bot)

### Integration with LLM

- [Paraworks/vits\_with\_chatgpt\-gpt3](https://github.com/Paraworks/vits_with_chatgpt-gpt3)
- [Minami\-Yuduru/\-ChatGPT\_VITS: 一个使用OpenAI接口链接VITS模型的语音对话系统GUI](https://github.com/Minami-Yuduru/-ChatGPT_VITS)

### Articles, Awesome Lists, News

- [VoiceConversionLab \(@VoiceConversion\) / Twitter](https://twitter.com/VoiceConversion)
- [zzw922cn/awesome\-speech\-recognition\-speech\-synthesis\-papers: Automatic Speech Recognition \(ASR\), Speaker Verification, Speech Synthesis, Text\-to\-Speech \(TTS\), Language Modelling, Singing Voice Synthesis \(SVS\), Voice Conversion \(VC\)](https://github.com/zzw922cn/awesome-speech-recognition-speech-synthesis-papers#Voice-Conversion)
- [Search \| arXiv e\-print repository](https://arxiv.org/search/?query=vits+voice&searchtype=all&source=header)
- [Search \| arXiv e\-print repository](https://arxiv.org/search/?query=vits+tts&searchtype=all&source=header)
- ["VITS" \- Google Search](https://www.google.com/search?q=%22VITS%22)
- [Search · vits](https://github.com/search?q=vits)
- [【機械学習】VITSでアニメ声へ変換できるボイスチェンジャー&読み上げ器を作った話 \- Qiita](https://qiita.com/zassou65535/items/00d7d5562711b89689a8)
- [2021年6月に発表された最新の音声合成手法「VITS」でアニメ風合成音声を作ってみた【つくよみちゃんコーパス】](https://shirowanisan.com/entry/2021/08/07/172736)
