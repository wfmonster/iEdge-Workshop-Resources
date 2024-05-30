Date: May 30 2024
## Section 1: Setup
**Demo Links**
- [OpenAI website](https://openai.com/)
- [ChatGPT website](https://chat.openai.com/)
- [OpenAI Playground](https://platform.openai.com/playground)
- [Replit](https://replit.com/)

**The Transformer Model**
- [Paper: Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf)
- [Visualizing LLMs](https://colab.research.google.com/drive/1hXIQ77A4TYS4y3UthWF-Ci7V7vVUoxmQ?usp=sharing)
- [Understanding Word2Vec](https://jalammar.github.io/illustrated-word2vec/)
- [Embedding Explorer](https://blog.echen.me/embedding-explorer/#/) 
- Tool: platform.openai.com/tokenizer
- Tokenizer: https://github.com/openai/tiktoken 
	- has an educational module
- Word Probabilities: https://platform.openai.com/playground/complete
	
Pitfalls Thinking Like LLMs - The Reversal Curse**
- [Paper: The Reversal Curse: LLMs trained on “A is B” fail to learn “B is A”](https://arxiv.org/pdf/2309.12288.pdf)

**Lesson: Artificial General Intelligence?**
- [Paper: Sparks of Artificial General Intelligence: Early experiments with GPT-4](https://arxiv.org/pdf/2303.12712.pdf)- [Paper: Levels of AGI: Operationalizing Progress on the Path to AGI](https://arxiv.org/pdf/2311.02462)

**Prompt Engineering**
- [Paper: Emergent Abilities of Large Language Models](https://arxiv.org/pdf/2206.07682)
- [Prompting Framework](https://www.canva.com/design/DAFnPkKRNds/UG4PAiQyep7zLCBU4HGRtA/edit?utm_content=DAFnPkKRNds&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

**Language Models are Few-Shot Learners**
- [Paper: Language Models are Few-Shot Learners](https://arxiv.org/pdf/2005.14165)

**How Many Examples?**
- [Paper: Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?](https://arxiv.org/pdf/2202.12837)

**Thinking Like LLMS - But Wait…**
- [Paper: Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?](https://arxiv.org/pdf/2202.12837)

**Chain-of-Thought Prompting**
- [Paper: Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/pdf/2201.11903)

**Lesson: Zero Shot CoT**
- [Paper: Large Language Models are Zero-Shot Reasoners](https://arxiv.org/pdf/2205.11916)

**Jailbreak!**
- [Paper: “Do Anything Now”: Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models](https://arxiv.org/pdf/2308.03825.pdf)

## **Parameter- efficient fine tuning (PEFT)**

- [**Scaling Down to Scale Up: A Guide to Parameter-Efficient Fine-Tuning**](https://arxiv.org/pdf/2303.15647.pdf) - This paper provides a systematic overview of Parameter-Efficient Fine-tuning (PEFT) Methods in all three categories discussed in the lecture videos.
    
- [**On the Effectiveness of Parameter-Efficient Fine-Tuning**](https://arxiv.org/pdf/2211.15583.pdf) - The paper analyzes sparse fine-tuning methods for pre-trained models in NLP.
    
## **LoRA**
- [**LoRA Low-Rank Adaptation of Large Language Models**](https://arxiv.org/pdf/2106.09685.pdf) - This paper proposes a parameter-efficient fine-tuning method that makes use of low-rank decomposition matrices to reduce the number of trainable parameters needed for fine-tuning language models.
    
- [**QLoRA: Efficient Finetuning of Quantized LLMs**](https://arxiv.org/pdf/2305.14314.pdf) - This paper introduces an efficient method for fine-tuning large language models on a single GPU, based on quantization, achieving impressive results on benchmark tests.
    
## **Prompt tuning with soft prompts**
- [**The Power of Scale for Parameter-Efficient Prompt Tuning**](https://arxiv.org/pdf/2104.08691.pdf) - The paper explores "prompt tuning," a method for conditioning language models with learned soft prompts, achieving competitive performance compared to full fine-tuning and enabling model reuse for many tasks.