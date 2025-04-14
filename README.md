# LLM-colours
Speed Run Research Project on the Manifold Which Colours lie on in an LLM.

Previous speed run: https://github.com/edwardbturner/CoT-intervention.

We have evidence that LLMs represent data in low dimensional minfolds within their residual streams (specifically days of the week/month as circles: https://arxiv.org/pdf/2405.14860). Well how about finding higher dimensional representations? Idea: Lets see how the models embed colours, which if you view in the classic RGB sense are very much a 3D object.

Initially I am going to attempt to do this directly on the residual stream for the following reasons:
(1) Easier, no SAE training neeeded
(2) Would be a stronger result to show the residual stream directly holds this 3D object
(3) I will be using very clean prompts so I'm not too worried about superposiiton noise (perhaps a poor argument)

We start at 18:35 on April 14th 2025.

UPDATE 1:
    - 19:30 have it working locally for gpt2-small, plot shows nothing clear, will try gemma 2B now

UPDATE 2:
    - 19:50 run on gemma-2B, nothing clear again although bit clearer grouping than gpt2 (especially in later layers), time to switch to pre-trained SAE! Just before that going to try gemma-9B, yeh okay still nothing clear.