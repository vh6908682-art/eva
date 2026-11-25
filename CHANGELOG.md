# Changelog

## [0.4.0](https://github.com/vh6908682-art/eva/compare/v0.3.1...v0.4.0) (2026-11-25)


### Features

* an animated pixel-art face for Eva ([7a8a267](https://github.com/vh6908682-art/eva/commit/7a8a267547db792ec074a163ea947135c1535e1e))
* autonomous mode and 'always allow' approvals ([c19bd86](https://github.com/vh6908682-art/eva/commit/c19bd86f29ef28d5d8dd9047db45890c8dd8a730))
* autonomy with heartbeat, follow-ups and an async terminal ([6b92f94](https://github.com/vh6908682-art/eva/commit/6b92f9412a34a12c9aef466dc7824f276349fcba))
* background tasks, interruptions and fuller speech ([550ec86](https://github.com/vh6908682-art/eva/commit/550ec86c94da705715a3affe95a7c58881243c73))
* configurable step limit, with a summary instead of an error ([3427953](https://github.com/vh6908682-art/eva/commit/3427953a5ef6c37bddbec288feaef1daf36c4313))
* configure Whisper's GPU precision with EVA_WHISPER_COMPUTE_TYPE ([8299923](https://github.com/vh6908682-art/eva/commit/82999230df02d97acfe038bbc7ef279cc4d14b8c))
* desktop notifications when tasks finish or need approval ([e50f43b](https://github.com/vh6908682-art/eva/commit/e50f43b9d64262c6f5260625a361172e8259f242))
* Eva follows through when she stops halfway through her plan ([011eaad](https://github.com/vh6908682-art/eva/commit/011eaad0df383c177616a9701b589220d42625a0))
* Eva keeps a visible plan for multi-step work ([ed75046](https://github.com/vh6908682-art/eva/commit/ed750467f8ae9ec951e1f0c765e3ad3daafcefc6))
* Eva keeps the user posted on long work ([c96af92](https://github.com/vh6908682-art/eva/commit/c96af92222b8c03615705127ff33714d07860f2e))
* eva's personality and docker setup ([b7d9be4](https://github.com/vh6908682-art/eva/commit/b7d9be4b8e6f12bb42446d8e4777e13c572c3507))
* first version with terminal, command approval and journal ([8982660](https://github.com/vh6908682-art/eva/commit/89826602133fc1c6f61d403011fc7d5995bab17b))
* gemini support and voice on the gpu ([bf64e25](https://github.com/vh6908682-art/eva/commit/bf64e259bcbcb33b3cbf844a40de05011ecd1bee))
* hands-free mode with speech detection (Silero VAD) ([7985b71](https://github.com/vh6908682-art/eva/commit/7985b717170f8a02bd94bd74f2d391284725be03))
* let eva propose changes to her own code ([e573dbf](https://github.com/vh6908682-art/eva/commit/e573dbf17fe7019a14c2aff8b95f7d7040a3b79a))
* let read-only commands discard errors and sort without approval ([4582b1a](https://github.com/vh6908682-art/eva/commit/4582b1adcb37a6f1964582d42edb37248befd8b2))
* messages sent mid-task reach Eva at her next step ([4b20160](https://github.com/vh6908682-art/eva/commit/4b201609c77f8ef9bfc79e87bd07109ac1d0c845))
* render Eva's replies as Markdown in the terminal ([e9b96ca](https://github.com/vh6908682-art/eva/commit/e9b96caf9d83aea8179650632052b8de42e1c741))
* report tool results and let Eva choose her expressions ([d2f5493](https://github.com/vh6908682-art/eva/commit/d2f54938ee520f11d2d3483c8eceee8189661394))
* self-extension through skills and reviewed source edits ([98eb163](https://github.com/vh6908682-art/eva/commit/98eb163e8ef53a6b4c9a378e83edd66a13a24c57))
* session summary in the journal ([19fb788](https://github.com/vh6908682-art/eva/commit/19fb78808eea48eb0d2766c9dcb4d69aabc64cb8))
* short startup line and a :help command ([e5d1e2a](https://github.com/vh6908682-art/eva/commit/e5d1e2ac66e20cd9d3edf25aed41c47712235f14))
* split-screen terminal with Eva's face ([98fcbf6](https://github.com/vh6908682-art/eva/commit/98fcbf6be73dbe1e3c911d6e709a23fa1f5a8ff6))
* status speech during turns, .env config ([40738e7](https://github.com/vh6908682-art/eva/commit/40738e754d539e55d26b022ab76998dd32cab8ed))
* stream events and speak while working ([319b6d1](https://github.com/vh6908682-art/eva/commit/319b6d18310c9d13840a818ec471940eab52f8fe))
* stream the reply to the terminal as it is written ([a03fc93](https://github.com/vh6908682-art/eva/commit/a03fc93a3c51adf1876e28605b23e0f699d16754))


### Bug Fixes

* :record hung waiting for an Enter that was never read ([042b003](https://github.com/vh6908682-art/eva/commit/042b003d29647a20d26cc883bc545fa342f2f422))
* an approval never gets stuck behind text already in the input box ([6b4048d](https://github.com/vh6908682-art/eva/commit/6b4048d047dc1440dd7e8fed6c08acfdbb36a318))
* explain how to install voice when it is missing ([acff77d](https://github.com/vh6908682-art/eva/commit/acff77da4f37f59bba583a9a8000be9ad700404a))
* fit the approval notice to the conversation pane ([b746272](https://github.com/vh6908682-art/eva/commit/b74627234ec6f4e6ddd4fe7f776e287a34c8b2ac))
* keep Eva's voice working after a sentence fails ([a26ca72](https://github.com/vh6908682-art/eva/commit/a26ca72562df2e6f7bacc24909ec7cfb6e38efe6))
* keep the Activity panel visible on short terminals ([afb1a7d](https://github.com/vh6908682-art/eva/commit/afb1a7d46258bd3a5275af749195e597d338d34b))
* keep the approval notice in the conversation to one line ([a1de0e6](https://github.com/vh6908682-art/eva/commit/a1de0e66f274f16d5814f9537fe4c181b2a9f359))
* long messages wrap in the input box instead of scrolling sideways ([842b086](https://github.com/vh6908682-art/eva/commit/842b08652329833454c1ea209e7521049843b804))
* only speak the text eva picks, report rejected actions ([23d55ba](https://github.com/vh6908682-art/eva/commit/23d55bac0b9f424577240c1c088765787343b2c8))
* run Whisper on the GPU with CUDA 12 cuBLAS, fall back to CPU ([2de3405](https://github.com/vh6908682-art/eva/commit/2de34052a9596d376322c29e31e029109cd2737b))
* say when the speech model is downloading or loading ([7288262](https://github.com/vh6908682-art/eva/commit/728826205d38a5e96dc1007e820a10419db757cb))
* tell Eva the current date and time on every model call ([1e1a31f](https://github.com/vh6908682-art/eva/commit/1e1a31fefd5c776506d0a345a7b4c6358aa71e66))
* tell the model whether speech is on, keep replies in English ([6e5fade](https://github.com/vh6908682-art/eva/commit/6e5fadef6781ba16b068ea3e8d97d3572c40832b))
* the status line names the reaction Eva's face is playing ([58d7646](https://github.com/vh6908682-art/eva/commit/58d76469390b64552d11d16203c94ab99c59a5ec))


### Performance Improvements

* repaint side panels only when their content changes ([4ec1441](https://github.com/vh6908682-art/eva/commit/4ec1441830bbf7b9626752f5de5ecc17b282d95c))
* run Whisper as int8_float16 on the GPU ([e5cf844](https://github.com/vh6908682-art/eva/commit/e5cf844254439e79256ee1b7ce412c75d259d3e2))
* stream speech by sentence and warm up the voice models ([85e4f29](https://github.com/vh6908682-art/eva/commit/85e4f292f61672457bcfe9f79a679d2de7d50f61))


### Documentation

* add a demo recording to the README ([5bc7dc5](https://github.com/vh6908682-art/eva/commit/5bc7dc5c852edc9874ab783f525db33488113df6))
* add MIT license, security policy and project metadata ([3e0c56c](https://github.com/vh6908682-art/eva/commit/3e0c56caf4d8c086ad56aaf4b4cc614e36b7d87a))
* contributing guide, issue forms and Docker user setup ([58b6c0c](https://github.com/vh6908682-art/eva/commit/58b6c0c9f4080ed7c1d4eb65e83b1432d781715f))
* document a local setup for a 6 GB GPU ([9bfd512](https://github.com/vh6908682-art/eva/commit/9bfd512f09765e73ef7c670bdf2772956fc41edc))
* note that voice needs Python 3.12 ([0af7db1](https://github.com/vh6908682-art/eva/commit/0af7db130b4992cb024dd4bc89135258128bbb5f))
* re-record the demo in 16:9 with the GitHub dark theme ([eab86f6](https://github.com/vh6908682-art/eva/commit/eab86f6cda8a57d5b40f7d2942dd99183023adc9))
* redesign the README ([71006b3](https://github.com/vh6908682-art/eva/commit/71006b32d72022bbd6db5a0bf6b1384d40b0ba9b))
* rewrite the README around running Eva locally ([95a65fd](https://github.com/vh6908682-art/eva/commit/95a65fd18332b7e6af43aaa06d8c9f155669d268))
* run the local model on llama.cpp or Ollama too ([c95b27c](https://github.com/vh6908682-art/eva/commit/c95b27c5f5e89c8ff4b0be215ad27abf13aeaad9))
* show the split screen and Eva's face in the README ([03f46b5](https://github.com/vh6908682-art/eva/commit/03f46b504b46403412b997b122b2a0836729dd41))
* use the recommended Qwen3.5 model in .env.example ([24f9c5c](https://github.com/vh6908682-art/eva/commit/24f9c5c66b7cdb024b7eb256b0de2a65fdaa5ae5))

## [0.3.1](https://github.com/Ilhe8l/eva/compare/v0.3.0...v0.3.1) (2026-10-15)


### Bug Fixes

* fit the approval notice to the conversation pane ([bf0b09d](https://github.com/Ilhe8l/eva/commit/bf0b09d1101b533c4f494382b87f0943b6f21965))
* keep the approval notice in the conversation to one line ([8839ef6](https://github.com/Ilhe8l/eva/commit/8839ef667c2edde3e930716914c835da581cb204))

## [0.3.0](https://github.com/Ilhe8l/eva/compare/v0.2.0...v0.3.0) (2026-10-08)


### Features

* Eva follows through when she stops halfway through her plan ([7757c66](https://github.com/Ilhe8l/eva/commit/7757c667e7cc7d6e28b84f2d813e169183dc8c0a))


### Bug Fixes

* tell Eva the current date and time on every model call ([2363d0f](https://github.com/Ilhe8l/eva/commit/2363d0f07b3f74370ff5ede58f9453a9b4cd44de))


### Documentation

* note that voice needs Python 3.12 ([2ce01d9](https://github.com/Ilhe8l/eva/commit/2ce01d9d95d801ec8ac97b22d7c8fe1f779e0d8e))
* run the local model on llama.cpp or Ollama too ([88db8ec](https://github.com/Ilhe8l/eva/commit/88db8eccfe576c41722ecf25a2af657e27b7cf8c))

## [0.2.0](https://github.com/Ilhe8l/eva/compare/v0.1.0...v0.2.0) (2026-09-29)


### Features

* an animated pixel-art face for Eva ([5f3a93a](https://github.com/Ilhe8l/eva/commit/5f3a93a28903211ddf2fbbb07891a9a86daebd51))
* Eva keeps a visible plan for multi-step work ([facf78d](https://github.com/Ilhe8l/eva/commit/facf78d03999e391283ed546188358ce476d4fc3))
* report tool results and let Eva choose her expressions ([e2cb0da](https://github.com/Ilhe8l/eva/commit/e2cb0da67b41490a2a1b359ca50262e49821dabd))
* split-screen terminal with Eva's face ([3420eb0](https://github.com/Ilhe8l/eva/commit/3420eb0bffbf403ef2736a4453c8d90b1416ba73))


### Bug Fixes

* an approval never gets stuck behind text already in the input box ([511e092](https://github.com/Ilhe8l/eva/commit/511e0924ed80a861e378c43a5d55482343c6f3d5))
* keep the Activity panel visible on short terminals ([71252d9](https://github.com/Ilhe8l/eva/commit/71252d95e54b1e5b01348d7054e5c4d36f84c269))
* long messages wrap in the input box instead of scrolling sideways ([315d83f](https://github.com/Ilhe8l/eva/commit/315d83f31d84798110553f0b274c39833d4f496b))
* the status line names the reaction Eva's face is playing ([f35595b](https://github.com/Ilhe8l/eva/commit/f35595b24421d6e7050ab987ebaec3ed4860bde3))


### Performance Improvements

* repaint side panels only when their content changes ([e930a16](https://github.com/Ilhe8l/eva/commit/e930a168af7dcfae281e047767e42280b89880bb))


### Documentation

* show the split screen and Eva's face in the README ([f69ea4c](https://github.com/Ilhe8l/eva/commit/f69ea4cdba7f5524860de34ffb0f0dba9adcecd7))

## 0.1.0 (2026-09-28)


### Features

* autonomous mode and 'always allow' approvals ([050e5f3](https://github.com/Ilhe8l/eva/commit/050e5f32d0029645f5c5379f5d1922cf949118c2))
* autonomy with heartbeat, follow-ups and an async terminal ([9a88239](https://github.com/Ilhe8l/eva/commit/9a882397e5668480aa5e9769d2d375ba424d4ca4))
* background tasks, interruptions and fuller speech ([a7ca8a0](https://github.com/Ilhe8l/eva/commit/a7ca8a04fbdccdce7ed73c56f533ca548b979a73))
* configurable step limit, with a summary instead of an error ([fe89a06](https://github.com/Ilhe8l/eva/commit/fe89a06eab988280388a3b13fbaf7bd3d0500341))
* configure Whisper's GPU precision with EVA_WHISPER_COMPUTE_TYPE ([8a4d92a](https://github.com/Ilhe8l/eva/commit/8a4d92a112214c9434c08ce693f4c694d662e075))
* desktop notifications when tasks finish or need approval ([9caf0b5](https://github.com/Ilhe8l/eva/commit/9caf0b5653ad22ecc96261fc80ee4dda0d526478))
* Eva keeps the user posted on long work ([4febccb](https://github.com/Ilhe8l/eva/commit/4febccb438c28d3d1d58a344ef2ac760f5c37c9f))
* eva's personality and docker setup ([ec1e5d7](https://github.com/Ilhe8l/eva/commit/ec1e5d73466ef287bf59d9796406d97e96d4f3be))
* first version with terminal, command approval and journal ([179d295](https://github.com/Ilhe8l/eva/commit/179d2955fb7110aef81e65b2a4a8fd342fce2803))
* gemini support and voice on the gpu ([0f6097a](https://github.com/Ilhe8l/eva/commit/0f6097a97518988f23cad18803325f921ccbd076))
* hands-free mode with speech detection (Silero VAD) ([3527184](https://github.com/Ilhe8l/eva/commit/3527184c3c88282925a9ce481c69a3ce261ddf76))
* let eva propose changes to her own code ([3c5a7e0](https://github.com/Ilhe8l/eva/commit/3c5a7e018ca014136f9af1d279a1f327bdf1c1eb))
* let read-only commands discard errors and sort without approval ([c959169](https://github.com/Ilhe8l/eva/commit/c9591693a69d56b57c42df7b962b308193c30da1))
* messages sent mid-task reach Eva at her next step ([8b8a376](https://github.com/Ilhe8l/eva/commit/8b8a37635a2887f56786e23c8ca89c596bc176a5))
* render Eva's replies as Markdown in the terminal ([39cc4d9](https://github.com/Ilhe8l/eva/commit/39cc4d91337347c2225adea7e58e7f57c0d514be))
* self-extension through skills and reviewed source edits ([72080d4](https://github.com/Ilhe8l/eva/commit/72080d4eab9ae13febb3cfdd0787686e1c3598cf))
* session summary in the journal ([2a0cc21](https://github.com/Ilhe8l/eva/commit/2a0cc214633c37b0db7edda3be9951188bc7f7e9))
* short startup line and a :help command ([317d550](https://github.com/Ilhe8l/eva/commit/317d550c493a078d2f94c019db6b1cd96f6ffca3))
* status speech during turns, .env config ([dcf63a1](https://github.com/Ilhe8l/eva/commit/dcf63a1f8226226a350189e300b13f6f826371b6))
* stream events and speak while working ([00a6c3a](https://github.com/Ilhe8l/eva/commit/00a6c3abc1782cba934e4a7ca5a01a2524338874))
* stream the reply to the terminal as it is written ([db4b343](https://github.com/Ilhe8l/eva/commit/db4b343542aff0a75dcabe7bdf89fd7cd9b8eb3f))


### Bug Fixes

* :record hung waiting for an Enter that was never read ([02fc6c5](https://github.com/Ilhe8l/eva/commit/02fc6c5105bd1c0a7bc50fa6b6705cd7f04c72db))
* explain how to install voice when it is missing ([954a52c](https://github.com/Ilhe8l/eva/commit/954a52cd59501f8b9a7a9ef541cb7bc9867c16a5))
* keep Eva's voice working after a sentence fails ([35d3f1d](https://github.com/Ilhe8l/eva/commit/35d3f1dd06392011fd6b6908654b762d56d3b95f))
* only speak the text eva picks, report rejected actions ([375ba4d](https://github.com/Ilhe8l/eva/commit/375ba4da59e9a5229a5071dd30764d5d689698cb))
* run Whisper on the GPU with CUDA 12 cuBLAS, fall back to CPU ([49990c4](https://github.com/Ilhe8l/eva/commit/49990c4b2187d60a82f9fd9c1e4a9444360e43ac))
* say when the speech model is downloading or loading ([b8fef05](https://github.com/Ilhe8l/eva/commit/b8fef05cf83fb8b8742c4c317b22dc2044b037a1))
* tell the model whether speech is on, keep replies in English ([007483e](https://github.com/Ilhe8l/eva/commit/007483e46caee118adc948bd581a9ee251650b8a))


### Performance Improvements

* run Whisper as int8_float16 on the GPU ([282ea29](https://github.com/Ilhe8l/eva/commit/282ea29447c2a776270b55ca2e3b8e3227236857))
* stream speech by sentence and warm up the voice models ([b214c38](https://github.com/Ilhe8l/eva/commit/b214c38dc5d7e6a052c761497b5ca4e5feb868b4))


### Documentation

* add a demo recording to the README ([608eac4](https://github.com/Ilhe8l/eva/commit/608eac4a331d2de7289cae96111e371071310831))
* add MIT license, security policy and project metadata ([500ec7e](https://github.com/Ilhe8l/eva/commit/500ec7eba1189bad5b72e4b4364a219b94fbb423))
* contributing guide, issue forms and Docker user setup ([feec1d8](https://github.com/Ilhe8l/eva/commit/feec1d81d95b66eebd27f9cb72999c3042867dd6))
* document a local setup for a 6 GB GPU ([5ecd0f9](https://github.com/Ilhe8l/eva/commit/5ecd0f967be779bcc1adb2231bc6a577d7b1d5d4))
* re-record the demo in 16:9 with the GitHub dark theme ([d7d90ef](https://github.com/Ilhe8l/eva/commit/d7d90ef16f6aa78ea6f24cbaab0f0ca2d27d42d6))
* redesign the README ([b088c0e](https://github.com/Ilhe8l/eva/commit/b088c0e01a8e95999bc2a0515ee9bec7456d7a7e))
* rewrite the README around running Eva locally ([6b52c56](https://github.com/Ilhe8l/eva/commit/6b52c56284a0a15d88e4a9f6ce4bdd13cf8a3816))
* use the recommended Qwen3.5 model in .env.example ([4d47f81](https://github.com/Ilhe8l/eva/commit/4d47f81e23ed973551c5fce988401013b382277f))
