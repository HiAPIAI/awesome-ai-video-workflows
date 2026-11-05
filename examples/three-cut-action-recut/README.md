# External completed case: three cuts and a voiceover payoff

[简体中文](README.zh-CN.md) · [Back to the case index](../../README.md#worked-product-video-cases)

**State: completed external artifact.** The SeedanceCheap team produced this example with Codex AI assistance, using earlier owned AI footage, a completed local Kokoro English voice and a Studio 2 Video Editor export. Captions and sound finishing were done locally. This is not a HiAPIAI output, a fresh model-generation test, a customer order or evidence of advertising performance. The contributor is affiliated with SeedanceCheap.

## Task and complete files

Turn an existing vertical action master into a short joke: a courier protects a delivery bag during a fight, then eats the cake. The fictional client's line is: “I said protect the cake. Not eat the cake.” The people and action are synthetic; the line is a script, not a customer testimonial.

- [Watch the complete 6.4-second result and switch to the 18.9-second master](https://pesoszpesosz.github.io/seedancecheap-video-cookbook/make-a-scene.html#protect-the-cake).
- [Open the finished MP4](https://pesoszpesosz.github.io/seedancecheap-video-cookbook/protect-the-cake-720p.mp4).
- [Inspect the clean public master](https://pesoszpesosz.github.io/seedancecheap-video-cookbook/action-master-clean-720p.mp4).
- [Inspect the completed reference voice](https://pesoszpesosz.github.io/seedancecheap-video-cookbook/cake-punchline-kokoro.wav).

The master was assembled from earlier footage; its length is not a single generation request length. Media stays at the publisher's canonical URLs. No media, account identifiers, keys or tracking parameters are bundled here.

## Source clock and output clock

Use the original source clock for each in/out pair. The third clip begins at 3.8 seconds of the assembled edit, not at 12.1 seconds of the output.

| Clip | Source in → out | Nominal length | Output interval | Story role |
| --- | --- | --- | --- | --- |
| 1 | 5.0 → 7.2 s | 2.2 s | 0.0 → 2.2 s | Establish the fight and bag |
| 2 | 7.6 → 9.2 s | 1.6 s | 2.2 → 3.8 s | Escalate the protection |
| 3 | 12.1 → 14.7 s | 2.6 s | 3.8 → 6.4 s | Reveal the cake and land the line |

1. Inspect the complete source and choose usable action before generating another take.
2. In the native case, select the corresponding video already visible in the media library three times. Set the source ranges above, 9:16 full-frame fit, 1× speed, original look and no transitions.
3. Keep original action audio for the first two clips. Put the completed voice on the last clip at voice volume 1 and reduce that clip's original audio to 0.1. Use no global soundtrack. The reference line lasts 2.474667 seconds and fits the 2.6-second final clip; do not stretch it across all three clips.
4. Review the complete export quote, then export. Download the result before its displayed expiry.
5. Add the shown captions and normalize the mixed audio locally. Inspect the finished MP4; the final captions and sound are not claimed as native editor output.

The native case used a voice already present in its account library. A linked WAV does not establish that arbitrary WAV import is supported. A source must actually be visible and selectable before quoting; do not treat an upload-success message alone as proof that a clip was added.

## File and QC evidence

| Public artifact | Encoded size | Container duration | Bytes | SHA-256 |
| --- | --- | --- | --- | --- |
| Finished MP4 | 720 × 1280 | 6.420638 s | 1,999,728 | `b8c589f0bddd1696c11828d782abce62e840d807a26e714460d72122b7280f46` |
| Clean public master | 720 × 1280 | 18.920638 s | 6,124,066 | `a4379d145b88c7fcbcf40dd90d4059f09e75fd5310206104b3c4c595ac12c874` |

The 6.4-second cut plan and container duration differ slightly. No source upscaling, frame interpolation or new source generation was used for this recut. Checks recorded a complete FFmpeg decode, readable captions in sampled frames, and the fight-to-cake reveal. A waveform check located the full reference voice at about 3.845 seconds in the received export (normalized correlation 0.962). This supports placement and completeness, not subjective listening quality or a universal lip-sync claim. Face, movement and prop consistency remain review tasks.

## Cost and availability boundary

The completed voice used 0.25 credit and the native edit used 0.5 credit: 0.75 credit total. At the optional $99 upfront pack of 100 credits, that allocates exactly $0.7425, about $0.74, to those two operations. Source/reference generation, local finishing and additional versions are separate. This is not an individual $0.74 checkout or a comparison with other providers.

On November 5, 2026 at 05:48 UTC, a fresh Kokoro attempt returned busy. The earlier completed voice and film remain inspectable; this case does not promise current narration capacity. A separate new budget-model identity review also means these earlier films must not be used to validate that route's model or price. Check the selected tool and complete quote before buying or starting; this document makes no paid request.

The reusable lesson is to separate source selection, edit timing, voice fit, finishing, allocated usage cost and successful delivery. A technical success does not establish that a scene fulfilled every creative instruction or sold the advertised product.
