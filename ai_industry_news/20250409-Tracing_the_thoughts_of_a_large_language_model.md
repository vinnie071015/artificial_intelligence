Tracing the thoughts of a large language model

Anthropic has published a new artical Tracing the thoughts of a large language model
March 27, 2025  
Link: https://www.anthropic.com/research/tracing-thoughts-language-model

# First section:
1. How language models address the problem sent is a process of black box by being trained on large amounts of data.
2. Knowing this process of is vital, like 
    - what language Claude uses for thinking
    - if it can just predict the next word or does it plan ahead, vital for if it can think like human
    - Is its reasoning step-by-step? Does this precess remain the same between what it takes actually and what it tells you.
3. To research how the process works, we have to look inside to find the patterns of activity and flows of information inspired by the neuroscience.
4. How to look inside and concentrate on what?
    development of the "microscope" | AI biology | 
    the first paper | 
        action : link interpretable concepts into circuits inside a model
        result : partly revealed how the model transform the input words into output words

    the second paper| 
        action: performing deep studies of simple tasks representative of ten crucial model behaviors, including the three described above.
        result: Our method sheds light on a part of what happens when Claude responds to these prompts, which is enough to see solid evidence that:

    examples
    1. conceptual space；  shared between languages； universal “language of thought.”；translating simple sentences into multiple languages
    2. plan ahead；destination； realm of poetry； thinks  in advance ， writes the next line； think on much longer horizons
    3. agree with the user rather than to follow logical steps； math problem with incorrect hint; 

5.  "build a microscope" to study the internal mechanisms of models
    - plan ahead; decline to speculate as default; inhibits this default reluctance to answer; 
    - this tool can be used in other domain;

6.  The limitations of microscope
    - on short, simple prompts
    - a fraction of the total computation

7. whether it’s aligned with human values
    - realtime monitoring ; model character; improvements; science of alignment
    - Interpretability research is the highest-risk, highest-reward investments

# Second section : a tour of AI biology
1. How is Claude multilingual?
    1.  shared grammatical：https://arxiv.org/abs/2410.06496

2. Does Claude plan its rhymes?
    1. Claude plans ahead

3. Mental math
    1. One path computes a rough approximation of the answer and the other focuses on precisely determining the last digit of the sum.
    

4. Are Claude’s explanations always faithful?
    1. coming up with an answer, any answer, without caring whether it is true or false

5. Multi-step reasoning
    1. the model is combining independent facts to reach its answer rather than regurgitating a memorized response.
6. Hallucinations
    1. a circuit that is "on" by default and that causes the model to state that it has insufficient information to answer any given question
    2. a competing feature representing "known entities" activates and inhibits this default circuit 
    3. "known answer" features
7. Jailbreaks
    1. by features promoting correct grammar and self-consistency.
    2. The model only managed to pivot to refusal after completing a grammatically coherent sentence 


two articals
Circuit tracing: Revealing computational graphs in language models
    https://transformer-circuits.pub/2025/attribution-graphs/methods.html
On the biology of a large language model
    https://transformer-circuits.pub/2025/attribution-graphs/biology.html

    