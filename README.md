# 1. Neural Rule-Execution Tracking Machine For Transformer-Based Text  Generation

Yufei Wang, Can Xu, Huang Hu, Chongyang Tao, Stephen Wan, Mark Dras, Mark Johnson, Daxin Jiang

- links: [abs](https://arxiv.org/abs/2107.13077) | [pdf](https://arxiv.org/pdf/2107.13077)
- [cs.CL](https://arxiv.org/list/cs.CL/recent)
- links: [pdf] (https://proceedings.neurips.cc/paper/2021/file/8ce241e1ed84937ee48322b170b9b18c-Paper.pdf)

Sequence-to-Sequence (S2S) neural text generation models, especially the pre-trained ones (e.g., BART and T5), have exhibited compelling performance on various natural language generation tasks. However, the black-box nature of these models limits their application in tasks where specific rules (e.g., controllable constraints, prior knowledge) need to be executed. Previous works either design specific model structure (e.g., Copy Mechanism corresponding to the rule "the generated output should include certain words in the source input") or implement specialized inference algorithm (e.g., Constrained Beam Search) to execute particular rules through the text generation. These methods require careful design case-by-case and are difficult to support multiple rules concurrently. In this paper, we propose a novel module named Neural Rule-Execution Tracking Machine that can be equipped into various transformer-based generators to leverage multiple rules simultaneously to guide the neural generation model for superior generation performance in a unified and scalable way. Extensive experimental results on several benchmarks verify the effectiveness of our proposed model in both controllable and general text generation.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">An interesting general approach to augment a transformer with logical predicates to control attributes of generation<br>Neural Rule-Execution Tracking Machine For Transformer-Based Text Generation: Yufei Wang, Can Xu, …, Mark Dras, Mark Johnson, Daxin Jiang<a href="https://t.co/Tkv89KsGaL">https://t.co/Tkv89KsGaL</a> <a href="https://t.co/zUdFhPA2ok">pic.twitter.com/zUdFhPA2ok</a></p>&mdash; Stanford NLP Group (@stanfordnlp) <a href="https://twitter.com/stanfordnlp/status/1420570721344917506?ref_src=twsrc%5Etfw">July 29, 2021</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Neural Rule-Execution Tracking Machine For Transformer-Based Text Generation<br>pdf: <a href="https://t.co/UgFUIvLwUU">https://t.co/UgFUIvLwUU</a><br>abs: <a href="https://t.co/jhpkwTteGR">https://t.co/jhpkwTteGR</a><br><br>can be equipped into various transformer-based generators to leverage multiple rules simultaneously to guide the neural generation model <a href="https://t.co/BOPKkpZsIw">pic.twitter.com/BOPKkpZsIw</a></p>&mdash; AK (@ak92501) <a href="https://twitter.com/ak92501/status/1420544955118936070?ref_src=twsrc%5Etfw">July 29, 2021</a></blockquote>
# 2. Mention Flags (MF): Constraining Transformer-based Text Generators<br>
https://aclanthology.org/2021.acl-long.9.pdf<br>
https://github.com/GaryYufei/ACL2021MF
