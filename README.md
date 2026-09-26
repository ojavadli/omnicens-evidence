# OmniCens — aggregate evidence

**OmniCens: Self-Improving Distillation for Multimodal Classification of Millions of Profiles**  
Orkhan Javadli and Anni Zimina  
Evidence snapshot: September 26, 2026.

This small research snapshot reports two separate prospective prediction rounds. It contains aggregate results only. The project title states the intended scope; these experiments do not establish million-profile performance.

| Round | People | Teacher-known decisions | Warm model agreement | Relevant majority baseline |
|---|---:|---:|---:|---:|
| 1 | 6 | 487 / 5,766 (8.45%) | 276 / 487 (56.67%) | 286 / 487 (58.73%) |
| 2 | 4 | 1,816 / 3,844 (47.24%) | 1,221 / 1,816 (67.24%) | 1,271 / 1,816 (69.99%) |

In round 1, warm adaptation also trails the cold model (278/487). In round 2, additional training gains nine known decisions over the held-fixed warm model (1,212/1,816), a 0.50 percentage-point difference, while remaining below the updated majority baseline. The four person-level paired differences have a mean of +0.90 points and a range of −0.16 to +3.03 points. Four people do not support a significance or reliable improvement claim.

The JSON preserves exact numerators, denominators, coverage, and answers on teacher-unknown decisions. In round 2, both warm models answer 2,020 of 2,028 teacher-unknown decisions. These answers are not counted as demonstrated factual errors or correct answers. The additional local adaptation preceding round 2 took 27.15 seconds of wall time and 5.319 process-tree CPU seconds; that measurement excludes teacher work and input encoding.

Teacher agreement is **not human-verified accuracy**. The rounds use different training histories and are not pooled. Decisions within one person are not independent samples. Source delivery and output validation do not certify semantic-policy conformance or teacher correctness. No quality parity, tenfold efficiency, or million-profile experimental result is established.

No individual records, handles, images, ontology field names, model files, or implementation are included. This evidence bundle does not claim conference acceptance.
