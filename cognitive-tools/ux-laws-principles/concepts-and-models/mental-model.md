---
description: A user's internal, compressed idea of how a system or product works.
---

# Mental Model

A Mental Model is a person's subconscious representation of how a system or product works. It is a compressed, internal working model built from past experience, assumptions, and beliefs.

In User Experience (UX) design, the user's mental model is often seen as the ultimate measure of success. When a product's interface aligns perfectly with what the user _expects_ it to do, the experience feels intuitive, effortless, and fast. When there is a mismatch, the user becomes confused, frustrated, and makes errors.

This is often summarised by Jakob's Law:

> "Users spend most of their time on other sites. This means that users prefer your site to work the same way as all the other sites they already know."

#### The Three Key Models

To design effectively, it's helpful to distinguish between the model inside the user's head and the model the designer creates:

1. **The User's Mental Model** (The Model We Seek):
   * What the user _believes_ about the system, based on their experience with similar products, real-world metaphors, and cultural standards.
   * Example: When a user sees a shopping cart icon, their mental model tells them that clicking it will show them a list of items to purchase, not a list of past orders.
2. **The Designer's Mental Model** (The Model We Must Discard):
   * What the designer or developer knows about the system's inner workings, architecture, and logic.
   * Challenge: Designers must actively avoid the trap of assuming that because a feature is logically organised internally, it is intuitively organised externally.
3. **The System's Conceptual Model** (The Model We Create):
   * The simplified, visual, and textual representation of the system presented to the user through the interface.
   * Goal: To make the Conceptual Model as close as possible to the User's Mental Model to minimize friction.

#### Aligning the Design with User Expectations

The gap between the User's Mental Model and the System's Conceptual Model is a direct measure of poor usability.

Here is how to close that gap:

**1. Prioritise Familiar Metaphors**

* Goal: Leverage the user's existing knowledge and reduce the need for learning.
* Application: Use design patterns that are universal. The "magnifying glass" for search, the "home" icon to return to the dashboard, and a right-facing arrow for "Next" or "Continue" are global mental models.

**2. Maintain Internal Consistency**

* Goal: Once a user learns how one part of your product works, they expect similar parts to function the same way.
* Application: If a double-tap opens a photo gallery on one page, a double-tap should open a video player on a different page. If you use a green button for the primary action on the checkout page, do not use a green button for the "Cancel" action on the confirmation page.

**3. Support Error Prevention**

* Goal: Anticipate that users will operate based on their mental model, which may be inaccurate.
* Application: Provide clear affordances (visual cues that suggest how to use an object). For example, a button that looks depressed suggests it is clickable, while a form field that is greyed out suggests it is uneditable.

**4. Conduct User Research**

* Goal: Directly observe the user's mental model, rather than guessing.
* Application: Use methods like Card Sorting to see how users _group_ and _label_ your content, and Usability Testing to watch where they get confused, revealing mismatches between their expectations and your design.

#### The Risk of Misalignment (Mental Model Discordance)

When the design strongly violates a user's mental model, the consequences are immediate:

* User Error: The user attempts an action that their mental model suggests is correct, but which the system does not support. (e.g., clicking the logo in the centre of the page, but it doesn't take them home).
* Frustration: They are forced to stop their task and spend cognitive energy figuring out the interface, leading to abandonment.
* Decreased Trust: They perceive the system as "broken" or "illogical," not themselves.

The take-away: Your interface should not require the user to learn a new language. It should speak the language of their experience.

#### Further Reading

{% embed url="https://www.nngroup.com/articles/mental-models/" %}

{% embed url="https://thedecisionlab.com/reference-guide/design/mental-models" %}
