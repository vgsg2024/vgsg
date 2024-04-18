# Visually Grounded Story Generation Challenge (VGSG)

Shared task on multimodal story generation at the Generation Challenges at INLG 2024

# Overview

Introducing the Visually Grounded Story Generation (VGSG) Challenge, a shared task at the Generation Challenges ****at [INLG 2024](https://inlg2024.github.io/)! Our goal is to generate coherent and visually grounded stories from multiple images using vision and language models.  

- Download the training data from [Hugging Face Datasets](https://huggingface.co/datasets/tonyhong/vwp) or [Github Repository](https://github.com/vwprompt/vwp).
- Come back here for the evaluation pipeline on May 1.
- Model output due **June 1, 2023, 23:59 anywhere on Earth (UTC-12)**. Submit on the shared task page on [Dynabench](https://dynabench.org/).
- System report submission due **June 15, 2023, 23:59 anywhere on Earth (UTC-12)**. Submit on [OpenReview](https://openreview.net/).

Here is our call for participation. 

Feel Free to join the [Discord Server](https://discord.gg/Wzu9qRa3Bs) if you have any questions for the organizers.  

More details can be found in the following. 

# Call for Participation

This task invites enthusiasts in vision-and-language integration to push the boundaries of vision-based story generation. The goal of this shared task is to generate stories grounded on a sequence of images. Participants will explore the intricate relations between visual prompts and textual stories, fostering innovations in techniques for coherent, visually grounded story generation. This task is particularly challenging because: 1) the output story should be a narratively coherent text with multiple sentences, and 2) the protagonists in the generated stories need to be grounded in the images. In addition, we also elicit submissions to fine-tune existing multimodal models efficiently, which is exciting for both industry and academics. 

Major progress has been made by the industry in vision-based text generation in the last few years. While generating descriptions from images or videos is widely available, grounded story generation is not evaluated. Investigating vision-based story generation requires several capabilities including commonsense reasoning and content planning. 

We're calling for submissions that demonstrate novel approaches to generating narratives that are not only coherent but also visually grounded. We particularly welcome participants to explore the following aspects of multimodal story generation: 

- Retrieval Augmented Generation
- Active Learning or Curriculum Learning
- Human-in-the-loop Generation
- Psycholinguistics-Driven Methods
- Parameter-Efficient Fine-Tuning
- Self-Supervised Learning
- Reinforcement Learning
- Generative Adversarial Network and Diffusion Models

We will employ both automatic and human evaluations. Whether it's through advanced computational models, innovative narrative techniques, or groundbreaking data handling methods, your contribution can help illuminate the paths toward more intuitive, human-like story generation from visual inputs. Join us in this endeavor to bridge the gap between visual prompts and story generation, and help set the stage for the next leap in vision and language research. 

# Get Started

To demonstrate the idea and help you get started quickly, we built a very simple baseline using OpenAI vision and GPT-4. 

# Dataset

We use a high-quality crowdsourced dataset **[Visual Writing Prompts](https://vwprompt.github.io/)** for training, validation, and testing.  ****

# Guidelines

Participants need to submit their generated stories together with a system description to the shared task page on [Dynabench](https://dynabench.org/). 

# Organizers

Xudong Hong (Saarland University)

Asad Sayeed (University of Gothenburg)

Vera Demberg (Saarland University)
