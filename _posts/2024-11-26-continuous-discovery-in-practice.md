# My First Dip into Continuous Discovery

_**Note:** Specific details about the actual onboarding flow and its implementation have been left out for confidentiality, so this post focuses on the approach and lessons learned._

---

## The Painful Product Onboarding

About a year ago, we faced a major issue. One of our product’s onboarding flows was driving users away. Nearly **70%** of them were dropping off before they even attempted the process. Support lines were overwhelmed with calls from users who needed help to complete what should have been simple.

The culprit? New regulations that required tougher security measures during onboarding. These changes hit us hard. Before the regulations, our conversion rates were over **90%**. Afterwards? They crashed to just **30%**.

But it wasn’t just about the numbers. The user feedback painted an even bleaker picture. Negative comments skyrocketed. One user summed it up perfectly: _“This feels impossible. Why make it so hard?”_ The frustration was palpable, and the damage to our business was real. We had to act.

---

## Enter: Continuous Discovery

At the time, we didn’t have a UX designer to tackle the problem, and leadership wasn’t pushing for a fix. Resources were stretched thin, and other priorities dominated the backlog. But I’d recently started reading _Continuous Discovery Habits_ by Teresa Torres, and her approach seemed like exactly what we needed.

Continuous discovery isn’t a one-time research project. It’s about building a habit of ongoing customer engagement to uncover insights and test ideas. The goal is simple: make sure your solutions address real user needs and align with business outcomes.

Here’s how I applied it:

- **Set a Product Outcome:** Improve onboarding conversion rates while complying with regulations.
- **Identify Opportunities:** Collect data from customer-facing staff and users to uncover pain points.
- **Test and Iterate:** Develop hypotheses, test solutions, and refine based on what we learned.

---

## Discovery in Action: Part 1 – Understanding the Problem

The first step was talking to the people closest to the users—our customer support team. I asked two straightforward questions:

1. _What challenges are users facing?_  
2. _What are their biggest frustrations or unmet needs?_  

Their responses were revealing. Many users felt overwhelmed by the process before even starting. One support agent shared this story:  

> _“A user called me, almost ready to give up. She was worried about making a mistake. But after I guided her through it, she said, ‘Oh, that was easier than I thought!’”_  

To validate these insights, I worked with our engineers to set up feedback tools at key points in the onboarding flow. We focused on the welcome page—the first thing users saw. This was a deliberate effort I initiated with our engineering team, ensuring the feedback tools were strategically placed based on where we saw users drop off in the quantitative data.

The data confirmed what we suspected: most users dropped out before even attempting the flow. The issue wasn’t the process itself—it was **user perception**. Many users assumed the flow would be too difficult to manage without support.

---

## Discovery in Action: Part 2 – Testing Solutions

Armed with this insight, I worked with the engineering team to form a hypothesis:  
_“If we can reassure users on the first screen and guide them better, they’ll be more likely to proceed.”_  

Equally, we wanted to direct users to the mobile app, where onboarding was simpler due to fewer regulatory requirements. This led us to redesign the first screen, making it more welcoming and informative.

To test our hypothesis, we ran an A/B/C test since the flow received **100k+ monthly users**:

- **Control (A):** The original screen with a plain informational message and a “Next” button.
- **Version B:** A nudge encouraging users to complete the product onboarding in the app.
- **Version C:** The same as Version B but with a guiding graphic to make the process clearer.

---

### The Results

After two weeks, the results came in:

- **Control (A):** **30%** conversion rate. Most users dropped off after the first screen.
- **Version B:** **65%** conversion rate (+35%). The nudge reduced drop-offs but frustrated some users, who found it _“pushy.”_
- **Version C:** **72%** conversion rate (+42%). The guiding graphic improved clarity and led to the best results.

While we were thrilled with the improvement, we weren’t done.  

Some users found the nudge in **Version B** frustrating, describing it as _“pushy.”_ We addressed this in subsequent iterations by making the redirect optional but strongly recommended. We also enhanced the guiding graphic in **Version C** based on user feedback, adding clearer instructions and reassurance about the process.

I kept the conversations with our customer-facing teams going throughout this process. One support agent later shared:  
> _“We’re getting fewer calls now. Users seem to understand what to do from the start.”_

This was backed by data. Support requests related to onboarding dropped by over **50%**, and user satisfaction scores for the flow improved significantly.

---

## Long-Term Impact

The success of this project had ripple effects beyond onboarding. By embedding continuous discovery into our process, we demonstrated the value of iterative, user-focused improvements. We began adopting similar practices in other projects, setting the stage for broader use of continuous discovery across the team.

From a business perspective, the impact was undeniable. Conversion rates returned to near pre-regulation levels. Support costs dropped, and user satisfaction increased, strengthening trust in the product.

---

## Lessons Learned

Looking back, this experience taught me a few key lessons:

1. **Perception Matters:** Users often decide based on how easy something _seems_, not how easy it actually is. Address perceptions early.
2. **Make Discovery a Habit:** Regularly talking to users helps you stay aligned with their needs and adapt quickly.
3. **Collaborate Across Teams:** Even without a UX designer, close collaboration between product and engineering can drive great results.
4. **Iterate with Purpose:** Small, incremental changes based on feedback can deliver big wins over time.

---

## Final Words

This project showed me the power of continuous discovery to solve tough challenges. By listening to users, testing ideas, and iterating, we turned a failing process into a success story.

If you’re facing a similar challenge, start by talking to your users. Their insights might surprise you—and they might just hold the key to solving your biggest problems.

And always remember: _don’t ship without a clear strategy tied to your product outcome._
