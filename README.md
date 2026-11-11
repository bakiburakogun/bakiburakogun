### Hi, I'm Burak.

I lead the open source team at Türkiye's Presidency of Migration Management. With my team I run its Linux infrastructure, build open source applications and fine-tune the **Bilge8** language models.

I build infrastructure from the bottom up: hardware at the base, a language model at the top.

---

#### I try to give back what I use

When I find a bug in the open source software we use, I fix it and send the fix upstream. So far, [58 of my pull requests](https://github.com/search?q=is%3Apr+is%3Amerged+is%3Apublic+author%3Abakiburakogun&type=pullrequests) have been merged across 20 open source repositories:

* **[Nextcloud Talk](https://github.com/strukturag/nextcloud-spreed-signaling/issues/1305)** — In clustered setups people were dropped from calls. I traced the cause and wrote the test.
* **[Talk live captions](https://github.com/nextcloud/live_transcription/pulls?q=is%3Apr+author%3Abakiburakogun+is%3Amerged)** — Video decoded for nothing, a language setting leaking between rooms, captions that never started; all five fixes were merged.
* **[vLLM](https://github.com/vllm-project/vllm/pull/55511)** — A tuned config for the NVIDIA A100; kernel time fell by 2.5% to 19.4%.
* **[GPUStack](https://github.com/gpustack/gpustack/pull/6177)** — Requests weren't spread evenly across model replicas; now they take turns evenly.
* **[Dify](https://github.com/langgenius/dify/pull/42532)** — The translation check missed broken placeholders; it now catches them in every language.

---

#### Language models

I fine-tune the [Bilge8](https://acikkaynak.goc.gov.tr/bilge8) models and am the principal investigator of our two projects, on TRUBA and on MareNostrum 5 in Barcelona. Outside work I'm also building models of my own: **Cezeri** and **Harezmi**.

Full story and stack: **[burakogun.com](https://burakogun.com/en/)** · **[LinkedIn](https://www.linkedin.com/in/baki-burak-ogun/)** · **[Hugging Face](https://huggingface.co/bakiburakogun)**
