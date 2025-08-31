Generative AI Explained (Q&A)

Generative Artificial Intelligence describes algorithms that can be used to create new, realistic content that reflects characteristics of the training data. It can produce a variety of content including audio, code, images, text, simulations, and videos. It has tremendous potential to help us become more productive. What are some applications of Generative AI?

	Image Synthesis such as DALL-E or Stable Diffusion
	Copilot for Software Development or Content Creation
	AI-Powered Search
	Language Modeling such as ChatGPT
	
Unlike discriminative artificial intelligence that performs classification tasks, modern Generative Artificial Intelligence uses machine learning and deep neural networks to understand and conditionally generate new examples from complex data distributions. What are some well-established architectures used to develop Generative AI?

	Modern Generative AI relies on several well-established architectures, each suited for different modalities (text, images, video, or 3D). The key ones are:

	1. Embeddings

	Used to represent high-dimensional and complex data (like text, images, or audio) in lower-dimensional vector space.

	Not a generative model by itself, but foundational for enabling similarity, conditioning, and retrieval in generative pipelines.

	2. Variational Autoencoders (VAE)

	Encoder–decoder architecture.

	Learns a compressed latent representation of data, then decodes to generate new samples.

	Commonly applied in image, video, and speech synthesis.

	3. Generative Adversarial Networks (GANs)

	Two components: Generator (creates synthetic data) and Discriminator (judges if it’s real or fake).

	Known for realistic image/video generation and creative applications (e.g., DeepFakes, style transfer).

	4. Diffusion Models

	Work by gradually adding noise to training data and then learning to reverse the noise process to generate new samples.

	State-of-the-art for high-fidelity image and video generation (e.g., Stable Diffusion, DALL·E 3).

	5. Transformers

	The backbone of Large Language Models (LLMs).

	Attention-based mechanism allows them to model long-range dependencies in sequences.

	Used in text generation (GPT-4, LaMDA, LLaMA), multimodal models (GPT-4V, Gemini), and even image/video generation with adaptations.

	6. Neural Radiance Fields (NeRF)

	Specialized for 3D content generation.

	Uses neural networks to reconstruct 3D scenes from multiple 2D views.

	Applied in AR/VR, gaming, and 3D
	
Which of the following are ways Generative Artificial Intelligence can transform the way we work?
Education & writing (creates ideas/text)

	✅ Healthcare & biology (generates candidates, proteins/drugs, simulations)

	✅ Agriculture (accepted here—think generative sims, planning, imagery enhancement)

	✅ Software development (generates code)

	✅ Geoscience (generates simulations/models)

	❌ Manufacturing: “perform defect detection” → discriminative

	❌ Cybersecurity: “detect attacks” → discriminative
	
Which of the following are accurate descriptions of how Generative Artificial Intelligence works?

	“Generative AI models use machine learning to understand patterns in the training dataset based on probability distribution in order to generate a new example based on these patterns.”
	✔ Correct – this is the core definition of how generative models work. They learn a probability distribution of the training data and then sample from it to generate new data.

	“Generative AI models share similarities with autocomplete.”
✔ Correct – especially for text generation. Large Language Models predict the next token in a sequence, much like autocomplete but far more powerful.