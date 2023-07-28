type:: [[📝 article]]
author:: [[Rylan Schaeffer]], [[Kateryna Pistunova]], [[Samar Khanna]], [[Sarthak Consul]], [[Sanmi Koyejo]]
topic:: [[computer science]], [[Prompt Engineers]], [[Prompt Stewards]], [[LLMs]] 
source:: [[arxiv]] 
url:: [link](http://arxiv.org/abs/2307.10573)

	- This study investigates the impact of logically invalid Chain-of-Thought (CoT) prompts on language model performance. The authors find that using logically invalid CoT prompts leads to similar performance gains as logically valid prompts on the most challenging tasks in the BIG-Bench benchmark. Additionally, they discover logical errors in some CoT prompts used in previous works, suggesting that factors beyond valid reasoning are responsible for performance improvements.
	- #### Key Takeaways
		- The use of logically invalid CoT prompts can significantly improve language model performance on challenging tasks.
		- Logically invalid CoT prompts achieve similar performance gains as logically valid prompts on the hardest tasks in the BIG-Bench benchmark.
		- Some CoT prompts used in previous works contain logical errors, indicating that factors beyond valid reasoning contribute to performance improvements.
		- Valid reasoning in prompting may not be the primary driver of performance gains, raising the need for further exploration of other factors influencing language model performance.
		- Future research should focus on understanding why models are robust to invalid CoT prompts, identifying features of data or prompts that lead to inconsistent or invalid outputs, and exploring the sensitivity of models to increasing degrees of incorrectness or the number of incorrect prompts.