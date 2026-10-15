# AI Accelerators 02 — SRAM Machines: Wafer-Scale, Compiler-Scheduled and Bulk-Synchronous

Put the weights in on-chip SRAM and memory bandwidth stops being the limit. The price is capacity: a whole wafer per few billion parameters, or hundreds of chips in a chain. Cerebras's wafer, Groq's statically scheduled LPU and Graphcore's bulk-synchronous IPU.

**Live site:** https://brendanjameslynskey.github.io/AI_Accelerators_02_SRAM_Machines/

Why SRAM; a wafer of 84 dies and how defects are survived; models split across wafers and weight streaming; the GroqChip's static schedule and a 576-chip chain; what the published speeds say about the bound; the IPU's bulk-synchronous tiles.

## Live, animated companion

This deck is the slide companion to [AI Accelerators Explained](https://ai-accelerators-explained.vercel.app), the Hardware-track site on the families of AI silicon:

- [Chapter 4: Wafer-scale](https://ai-accelerators-explained.vercel.app/learn/04-wafer-scale)
- [Chapter 5: Compiler-scheduled chips](https://ai-accelerators-explained.vercel.app/learn/05-compiler-scheduled)
- [Chapter 6: Reconfigurable dataflow](https://ai-accelerators-explained.vercel.app/learn/06-reconfigurable-dataflow)

## Where the numbers come from

Every number on these slides is computed at build time by the site's Python reference model ([`accel_model/`](https://github.com/BrendanJamesLynskey/ai-accelerators-explained/tree/main/accel_model)), the same code that writes its [results.md](https://github.com/BrendanJamesLynskey/ai-accelerators-explained/blob/main/results.md). Every hardware figure there has a source and an access date (2026-10-15); announced, retired and research parts are labelled, and vendor claims are quoted, never used as inputs. The numbers are the model's bounds; where a published figure exists, the slides compare them.

Part of the [AI Accelerators sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_AI_Accelerators) &middot; [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs)
