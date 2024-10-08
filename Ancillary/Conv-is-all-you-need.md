> This is a Slack message I sent to my advisor, one of his students, and the XRD group.
>
> Advisor never replied. My ideas went unappreciated.
>
> Today, some of my ideas, such as the ones below, are a mix of commonplace and still novel. Back then, they were extremely generous for me to share like this. His group appreciated me, but many of my ideas went unnoticed until years later.
>
> Meanwhile I was made to work across multiple lab groups throughout, writing different papers, contributing to two major grants, dealing with hospitalizations, and trying to build something more principled and long-standing that only I could do, while teaching concepts like this.
>
> This is a complete summary of the attention mechanism and its advantages, made more simple and general.

<img width="513" alt="SingleHeadAttention" src="https://github.com/slerman12/Template/assets/9126603/452f266d-d1dc-44d5-89e3-86f2734bf531">

I said I could summarize Attention in full detail intuitively in two sentences. I attempt that below.

“Attention is just a way to do weighted averaging of vectors produced via convolution.

Mathematically, it’s three convolutions producing three sets of feature vectors, followed by a matrix multiplication on two of those sets that produces “weights”, a Softmax on those weights that allows them to “weighted average”, and another matrix multiplication that finally “weighted averages” the third set and thereby yields the output of the attention.”

———

Comparative details:

What is the advantage of weighted averaging vectors? Well, like MLP it’s a global operation. Unlike global average pooling, it’s a global operation that can do relational reasoning between parts thanks to the dynamic weights. And unlike MLP, it’s faster and more parameter-efficient to operate via convolutions and at the vector-level than point-wise.

———

@Chenliang Xu The nice thing about the above conceptualization is we could create new vision transformers by just plug-and-play substituting convolutional layers with attention in existing CNNs. For example, a ResNet-ViT.

It’s strange that attention isn’t more widely thought of as convolutions because that simultaneously makes it simpler and more general.

@[student's name anonymized] if you ever want to make ViTs in UnifiedML, all of the above is implemented. I could use help with scaling to ImageNet or running smaller baseline experiments when UnifiedML is released if interested! The ViT space is really large.

The nice thing about the above though, it negates the need for patch embeddings. Just apply attention directly as a trio of convolutional kernels. Has anyone realized that in the newer ViTs? Can also make long text sequences much more efficient. (1D ViTs I’m referring to as Harmonic Transformers in UnifiedML).

Convolution is all you need :ballot_box_with_check:
