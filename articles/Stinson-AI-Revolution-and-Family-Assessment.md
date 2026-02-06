# The AI Revolution and Family Assessment

**Presenter:** Patrick Stinson
**Source:** YouTube Video Transcript
**URL:** https://www.youtube.com/watch?v=pQ5U65t1LEM

---

## Introduction: What Is the AI Revolution?

The key innovation driving everything right now is the ability for computers to understand language and reason with logic—in other words, to hear what you're trying to say in written language, and then to write back a response.

That innovation is called **Large Language Models (LLMs)**. They've used machine learning to iterate over and over again through tons and tons of text to learn how language works—for example, to understand what you wrote and to search through a knowledge base to respond.

---

## Part 1: How LLMs Work (The Basic Loop)

The most common way this is used today:

1. **Query** — Something like "F150 tire size" (can be full sentences or even rows of table data pasted as plain text)
2. **Search** — The LLM goes out into its domain of knowledge
3. **Pull** — It pulls out relevant information
4. **Write** — It writes back an answer (e.g., "270 by 17")

That's it—that's the full loop.

---

## Part 2: The BT Co-Pilot Feature

What I have done is add another component. Instead of going out to the general knowledge base that the LLM has been trained on (like what you get with ChatGPT), I have the LLM go to a **Bowen database**.

### The Bowen Database

It's got all of the Bowen literature in it. Instead of drawing from the general internet knowledge, it draws only from the Bowen literature.

The process:
1. You ask a question (e.g., "What is a triangle?")
2. It searches through all of that literature (which is very fast for computer software)
3. It pulls out the closest matches (5 to 50, tunable)
4. The LLM returns a response based on those passages (e.g., "A triangle is..." with citations)

### Why Only Bowen Literature?

This is where we start getting into some really nuanced stuff.

**The state-of-the-art in Bowen Theory:** There are no precise mathematical models to very precisely predict or diagnose a problem in a family, or to predict whether a certain intervention will alter that problem.

Despite what people in the mental health field want to believe—and also in the Bowen Network—formal scientific modeling requires proving or testing a hypothesis, which is essentially mathematics. There are exceptions to that, but the point for Bowen Theory is that **there are none of those models right now**.

We don't have a predictive mathematical model that will output a hypothesis for a family based on interview data. All we have is the **conceptual model**—derived from the literature.

---

## Part 3: The Conceptual Model Problem

### The State-of-the-Art

The model that's being executed—the rules, the algorithm that reads in information about a family and determines the course of actions and their likely outcomes—**is in the coach's head**. The brain is literally the material that the calculation gets performed on.

In order to have a coherent conceptual model in your head—one that doesn't conflict with itself—you've got to do a lot of reading and a lot of research. It takes a lot of time and interaction with others to sculpt your conceptual model that you act out in practice.

**We don't have a way to just type in a bunch of data and have a computer spit out an answer** like you can with medical databases ("What will the side effects of this pain medication be?"). It's not precise like that—it's conceptual, and it requires understanding.

### Testing the Model

To test whether somebody has a good enough conceptual model is within that relationship system: you use certain words that don't make sense to others, or your case presentations indicate you don't know what you're talking about, or you haven't learned to speak the language.

That just means your model needs more work, more training—there's nothing wrong with that.

### Low Resolution Science

A conceptual model is a low-resolution, low-detail way to be scientific. It's not very precise—it makes mistakes. It's like a really low-resolution image on a computer (say, 10 pixels) compared to 10 million pixels (which is what you get with accurate mathematics).

That's the conceptual model.

---

## Part 4: Why Bowen Theory Is Special

**Luckily for Bowen Theory, the conceptual model is essentially in the literature.**

It's not in one place—it's scattered throughout the literature—you have to pull from multiple sources, you have to have it all in your head.

But Bowen Theory is remarkably internally consistent. There's a remarkable amount of coherence. You can derive a lot of the conceptual model from the literature alone—you don't need as much of the person-to-person interaction as you do in another tradition like psychoanalysis.

I know that because that's how I came up. I'm obsessive with this kind of stuff. I was interested enough—I read all of the Bowen literature multiple times and mapped it all out. That's how you end up with a dissertation that's a thousand pages.

I'm not saying that to toot my horn—what I'm saying is: I know that it is possible to go through the literature. The literature is good enough. I kept it all in my head, and the result was that I entered the Bowen network and people understood what I was talking about. I was able to speak intelligently at a high rate.

**The literature is a good model for the state-of-the-art of Bowen Theory.** Not very precise, but at least there's a possibility of extracting the model from it.

---

## Part 5: The BT Co-Pilot Under the Hood

That Bowen database in the upper right—that's what I have.

LLMs can read the literature and understand it all—it basically has the conceptual model in there. So the conceptual portion can be conducted on the literature.

You can take that model—the one that a lot of us well-trained folks have in our heads, the one that lets us communicate freely between each other in a consistent way—and the LLM can more or less automate the application of the model by reading the Bowen literature.

### The Mechanics

In the BT Co-pilot feature:
1. You ask a question
2. It goes out to the database and looks for relevant passages
3. It uses an LLM again to spit back an answer

**The key is the LLM**—understanding language, reading words, and making the thing better.

What this is right now is a Stone Age form of *Homo sapiens*. This BT Co-pilot feature is the equivalent of finding an answer from the literature—and only the literature—so it gets that right. It doesn't go out to the internet like most models. Then it spits it back in a coherent way.

---

## Part 6: The Real Innovation — Building Blocks

### The Prompt Structure

What goes in the box? The way the LLM is utilized:

```
Here is timeline data:
[Plain text table with dates, conflicts, people involved]

Here are some academic excerpts to evaluate the timeline data:
[Passages from Bowen literature, e.g., "A triangle is..." from Kerr's book]

Based only on that timeline data, use the academic excerpts to answer this question:
[What are the key triangles?]
```

It's a three-part deal:
1. Take the Bowen Theory academic passages (that's the conceptual model)
2. Use that to analyze the timeline data
3. Answer the question based on that

You're just typing this out in plain text. The LLM only does one thing: it reads natural language and returns a response in English.

**The key is to figure out the right words**—"here's the timeline data," "based only on that timeline data," "use the academic excerpts to answer"—and then to add whatever gets the thing to be as useful as possible.

---

## Part 7: Where It Gets Really Cool — Chaining

This is where it gets really, really sophisticated—we don't even know how sophisticated we can make this.

You can:
1. Run this whole process on a small piece of the problem
2. Run a separate one on another piece
3. Run it three or four times on different small pieces

For example:
- Where are the key triangles?
- Where are the nodal events?
- What do you think the baseline anxiety is compared to the fluctuations?

You can divide it into all of these pieces, send each to an LLM, and then take the results and write a whole separate prompt that combines them:

```
LLM 1 → response
LLM 2 → response
LLM 3 → response
LLM 4 → response
      ↓
New prompt: "How do you summarize all of these four responses and make a suggestion?"
```

---

## Part 8: The Vision

This is the furthest my thinking has gone: **What are the building blocks you can make?**

You can make as many as you want and link them together.

What you're doing is **modeling Bowen Theory**—evaluating the family by breaking it into small pieces like these chunks, and then bringing them back together in whatever way they're supposed to fit together.

Questions to answer:
- How can we characterize the baseline level of chronic anxiety?
- What is the hypothetical baseline configuration?
- What are the triangles in this family?
- How does the baseline relate to the flare-up of anxiety?

All of these things are chunks. This is the chance—**the first chance**—to actually put the rubber on the road. It doesn't even have to be changing anything that's in Bowen Theory—it's actually **defining it more clearly**.

What are the pieces of an evaluation? What is Bowen Theory? Now we've got all this information and a conceptual model—we can build these building blocks to automate the processing of the data.

We could even have the data entry be a back-and-forth dialogue. We can have one button—"Evaluate"—that runs this whole script and spits out a report based on the data in the family diagram.

---

## Conclusion

This isn't going to be as good as a well-trained person right now. I can do better than this. But it is much better than nothing, much better than Google.

And the sky is the limit with how these building blocks can be put together.

**That's AI in a nutshell.** That's what everyone is freaking out about—the LLM has changed everything. Now everyone in industry is pouring trillions of dollars into trying to get the LLM better. But really, the boom is how to build applications like this—how to use these building blocks.

No one knows where the limit is. We just know that it's incredibly powerful.

So anyway, that's it. Now we just have to figure out what goes in those boxes, what to build with this kind of technology, and one brain is better than two with that.

Thanks a lot.
