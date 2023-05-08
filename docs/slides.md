---
theme: signalwerk
title: Conversational AI · an introductory session for Developers
---

```fm
style: negative
background: true
```

## Hello _👋_

# {{process.content.frontmatter.title}}

_Powercoders Bootcamp 2023-1_

<footer>

2023 · Zurich · Stefan Huber

</footer>

--s--

```fm
style: image
background:
  image: https://portrait.signalwerk.ch/illustration/2020/rgb/w4000/stefan-huber.jpg
  position: 50% 40%
```

## Stefan

<div class="box box--w40p box--bottom box--white box--padding small">

- Developer
- ❦ Typography

</div>

<footer class="footer--right">

Illustration by [Benjamin Güdel](http://www.guedel.biz/) · 2020

</footer>

--s--

## Objective of the session

- What is _Conversational AI_?
- How to use AI and _ChatGPT_ (& Copilot) in specific?
  - _optimize_ your **prompts**
  - give **context** & _engage_
- What is _your benefit_?
  - **problems** to solve
  - share your _findings_
- I try to build on top of [your curriculum](https://bootcamp.powercoders.org)

--s--

## Non-Objective of the session

> Today you will not learn how to develop/train AI-Models.

--s--

```fm
style: negative
background: true
```

## Check-In Round

# Share your _expectations & experiences_ <br> for this session

--s--

## Last 25 years were crazy

- **New approaches** in research ([LSTM in deep learing](https://en.wikipedia.org/wiki/Long_short-term_memory))
- **Neural networks** (similar to a brains) took over
- **Ability of computers** (chips/GPU specific for AI)

<footer>

[Sepp Hochreiter; Jürgen Schmidhuber (1997). "Long short-term memory". Neural Computation.](https://www.researchgate.net/publication/13853244_Long_Short-term_Memory)

</footer>

--s--

```fm
style: negative
background: true
```

## A new cultural practice

# _ethic_ & _moral_ vs **legal**

--s--

## ethic/moral/legal

- Is it ethical/legal to _learn from_ the data of _others_?
  - AI ← **people**
  - AI ← **other AIs**
- What kind of _decisions_ should be allowed by _AI_?
- _Bias and Discrimination_: how to _prevent_ it?
- …

<footer>

[Tagesanzeiger: Die Verwaltung darf jetzt künstliche Intelligenz nutzen – doch sie muss aufpassen](https://www.tagesanzeiger.ch/die-verwaltung-darf-jetzt-kuenstliche-intelligenz-nutzen-doch-sie-muss-aufpassen-370090350992) <br>
[Position der Digitalen Gesellschaft zur Regulierung von automatisierten Entscheidungssystemen](https://www.digitale-gesellschaft.ch/uploads/2022/02/Position-der-Digitalen-Gesellschaft-zur-Regulierung-von-automatisierten-Entscheidungssystemen-1.0.pdf)

</footer>

--s--

## legal · intellectual property

- Who owns the intellectual property created by AI? <br>ATM: _No IP from AI_ → because it’s not human thought!
- Who’s liable for _copyright infringement by AI_?

<footer>

[Reuters: Getty Images lawsuit says Stability AI misused photos to train AI](https://www.reuters.com/legal/getty-images-lawsuit-says-stability-ai-misused-photos-train-ai-2023-02-06/)

</footer>

--s--

## What is ChatGPT?

- _Large language model_ by **OpenAI**
- Uses _deep learning_ to generate **human-like** responses
- Trained on **massive text data**
- Capable of **answering questions** and engaging in _conversations_

> ChatGPT offers responses on virtually «any» subject.

--s--

## What is _GPT_?

- Acronym for _«Generative Pre-trained Transformer»_ (GPT-3 / GPT-4)

> Machine Learning gibberish…

--s--

## Practice · Demo

- Got to [chat.openai.com](https://chat.openai.com/chat)
- Create an account
- Answer the Question with the help of ChatGPT: <br> _What should we cover in this session about AI?_

--s--

```fm
style: negative
background: true
```

## Wait waht?!

# One step back…

--s--

## Why did we get answers?

- Who?
- How?
- Problems?

--s--

```fm
style: negative
background: true
```

## Who?

--s--

## Who is OpenAI?

- _2015_: `OpenAI, Inc.` is a **non-profit** research company
- _2019_: `OpenAI, L.P.` is a **for-profit** company
- profit capped to **100 times of investment**

--s--

## Recent history of OpenAI

- _2020_: GPT-3 released (language model)
- _2021_: DALL·E released (image model)
- _2022_: ChatGPT released (conversational model)
- _2023_: Large investment from Microsoft
- _2023_: GPT-4 released

--s--

## GPT-4 Performance

![](./img/gtp-4-performance.svg)

<footer>

Source: [March 14, 2023 – OpenAI Announcement](https://openai.com/research/gpt-4)

</footer>

--s--

## GPT-3.5 vs GPT-4

- GPT-3.5 → _fast_ & **not so smart**
- GPT-4 → _slow_ & **smarter**

<br>

### Rule of thumb

> _GPT-3.5_ is good enough for _common tasks_  
> Use _GPT-4 for developing_

--s--

```fm
style: negative
background: true
```

## How?

--s--

## Trained on «corpus»

- Crawled web
- WebText2
- Books1
- Books2
- Wikipedia

> later manually evaluated/ranked/curated

--s--

## No Internet _🧨_

- ChatGPT is **not a search engine**
- It is _not using «live» data_ from the web

> think of it as: someone had access to the web and learned on all data but is now offline

--s--

## Generative Pre-trained Transformer

![](https://openaicom.imgix.net/cf717bdb-0c8c-428a-b82b-3c3add87a600/ChatGPT_Diagram.svg)

--s--

```fm
style: negative
background: true
```

## Now that we know …

# Our answers

--s--

## Task

Q: What should we cover in this session about AI?

--s--

## Optimize

# Be specific

Q: What are the _five most important topics_ for a _workshop_ about _ChatGPT_?

--s--

## Optimize

# Give context

Q: In a **1.5h online training** session with **15 people**. What could be a good _time-table_ to learn in an efficient way **to prompt ChatGPT** for daily use as a **developer**? _Mark relevant information bold._

--s--

## Optimize

# Give Feedback

- Q: Please elaborate on …
- Q: Please give me an example of …
- Q: I didn’t like … but …
- Q: … is not correct. Please correct it.

--s--

## Optimize

- Feedback & chat-history matter
- Retry with different prompt
- Retry with same prompt

--s--

## Ask for the format

<div style="font-size: .8rem">
<pre>

Please name 10 inventors of the 20th century.
Response format should be: name, year, invention

</pre>
</div>

--s--

```fm
style: negative
background: true
```

## Problems?

What problems could we face with ChatGPT?

--s--

## Hallucinating

### Q: What are the three rivers in Winterthur?

- A: ... Töss, the Eulach, and **the Sulzerbach**
- A: … Töss … Eulach … **Thur** …

---

> Correct: Töss, Eulach, Mattenbach

<footer>

Different answers depending on the prompt, chat-history and language.

</footer>

--s--

## Bias

> Limitation: The models encode social biases, e.g. via stereotypes or negative sentiment towards certain groups.

- stereotypes
- gendered names
- regional names

<footer>

Source: [OpenAI: Limitations & risks](https://platform.openai.com/docs/guides/embeddings/limitations-risks)

</footer>

--s--

## Cut-off date

- Don't expect events/answers/facts/knowhow after **September 2021**

--s--

## Stereotype answers

- Most obvious thinking
- «Washed out» rewrites of the prompt

--s--

```fm
style: negative
background: true
```

## Let's try more

# A Prompt you know…

--s--

## Practice · Demo

- Ask ChatGPT to [validate a telephone number](https://bootcamp.powercoders.org/05-01-algorithms-programming-principles.html#/13) in a JavaScript function
- Use [jsfiddle (or similar)](https://jsfiddle.net/) not to loos time

--s--

## GitHub Copilot

- [GitHub Copilot](https://copilot.github.com/)
- AI pair programmer
- _Code_ & _comments_
- IDE integration
- Copilot is _not_ a _Chatbot_
- Copilot X will bring some improvements

--s--

## Copilot · Coding

> It writes code for you

- Think of it as _«machine partner»_
- You need to **communicate** with it

--s--

## Copilot · Coding · <small>`VSCode`</small>

- Trigger **Inline Suggestion** <small>`editor.action.inlineSuggest.trigger`</small>
- Show **Next** Inline Suggestion <small>`editor.action.inlineSuggest.showNext`</small>
- Show **Previous** Inline Suggestion <small>`editor.action.inlineSuggest.showNext`</small>
- GitHub Copilot: Open _Completions Panel_ <small>`github.copilot.generate`</small>

--s--

## Copilot · Coding

### Example

- You have an Array
- You want to extend it to a given size
- You want to fill it with a given number

```js
fillArray([1, 2, 3], 5, 0);
// [1, 2, 3, 0, 0]
```

--s--

## Copilot · lazy/stupid me

- what exactly was the _name_ again?
- skip _documentation_…
- bad with a certain _languages_

--s--

## Copilot · Labs

- _translate_ between languages
- _«enhance»_ code
- _comment_ on code

--s--

```fm
style: negative
background: true
```

## Questions?

# Ask them _now or later_

--s--

## Practice · Demo

### Example ChatGPT

- You have an Array
- You want to extend it to a given size
- You want to fill it with a given number

```js
fillArray([1, 2, 3], 5, 0);
// [1, 2, 3, 0, 0]
```

--s--

```fm
style: negative
background: true
```

## More complex

# ChatGPT

--s--

## Structure

- _Instruction_ first, **data** afterwards
- Ask for _format_

--s--

## Structure · Example

```txt
{{instruction}}
{{format}}

{{data}}
----
{{data}}

```

--s--

## Structure · Example

### Source

<div style="font-size: 0.6em">

```txt
PRS: Person, only the name of the person
CAT: Canton, state or federal state
CIT: City, municipality or political community
AUT: Authority, office
CMP: Company/Corporation
CRT: Court
​
PRS: 112
CAT: 245
CIT: 278
AUT: 276
CMP: 834
CRT: 377
```

</div>

--s--

## Structure · Example

### Required output

<div style="font-size: 0.6em">

```json
[
  {
    "short": "PRS",
    "index": 112,
    "text": "Person, only the name of the person"
  },
  {
    "short": "CAT",
    "index": 245,
    "text": "Canton, state or federal state"
  },
  {
    "short": "CIT",
    "index": 278,
    "text": "City, municipality or political community"
  }
  // …
]
```

</div>

--s--

## Structure · Example

<div style="font-size: 0.5em">

```txt
I have the following text and need out of it a JSON with the following structure:
An array of objects with the fields "short", "index" and "text".

​
here the text
----
PRS: Person, only the name of the person
CAT: Canton, state or federal state
CIT: City, municipality or political community
AUT: Authority, office
CMP: Company/Corporation
CRT: Court
----
​
here abrevaitions to index:
----
PRS: 112
CAT: 245
CIT: 278
AUT: 276
CMP: 834
CRT: 377
----
```

</div>

--s--

## Structure · Example

### Output

<div style="font-size: 0.5em">

```json
[
  {
    "short": "PRS",
    "index": 112,
    "text": "Person, only the name of the person"
  },
  {
    "short": "CAT",
    "index": 245,
    "text": "Canton, state or federal state"
  },
  {
    "short": "CIT",
    "index": 278,
    "text": "City, municipality or political community"
  }
  // …
]
```

</div>

--s--

## Structure · Example

```txt
{{instruction}}
{{format}}

{{data}}
----
{{data}}

```

--s--

## Structure · Example

Please add to the following function an error handling for the case that the `id` is not found in the `data` array. I'm a knowledged developer pleas only output the code no further explanation.

```js
function findDataById(data, id) {
  return data.find((item) => item.id === id);
}
```

--s--

## Use Cases

### Ask for ideas

> How would you implement a JavaScript function that takes a string and returns the number of words in it?

```js
countWords("Hello World!"); // 2
```

--s--

## Use Cases

### Ask for ideas

> How would you implement a JavaScript function that takes a string and returns the number of words in it? _Please reason about two possible implementations._

--s--

## Use Cases

### Small, stupid and fast

- [translate `curl`](https://chat.openai.com/c/773c8fb4-7f44-47de-bd36-c0b1dfed789a)
- [CDX fileformat](https://chat.openai.com/c/bae57a66-bce5-46b9-9ee5-c03e2d18c3df) [Example](https://web.archive.org/cdx/search/cdx?url=example.com/*&output=cdx)

--s--

```fm
style: negative
background: true
```

## but...

# We used now ChatGPT are there _alternatives_?

--s--

## Yes

### _Alternatives_ are available

- **Chat-Assistant** · [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)/[Vicuna](https://vicuna.lmsys.org/) (available ≠ free)
- **Get an image from text** · [Stable Diffusion](https://stability.ai/blog/stable-diffusion-public-release)
- **Generate text from audio** · [whisper](https://openai.com/research/whisper)
- …

--s--

```fm
style: negative
background: true
```

## exit 0; thx

# Questions?

--s--

```fm
style: negative
background: true
```

## exit 0; thx

# Feedback?
