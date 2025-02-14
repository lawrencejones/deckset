theme: Plain Jane, 2
text: Inter Tight, #ffffff
text-strong: Inter Tight Bold, #EE783F
header: Inter Extra Bold, #53585F
slidenumbers: true
slidecount: true

# GDPR Sub-processors

---

# What is GDPR, anyway?

- EU/UK data protection regulation
- We are a *processor* of customer data
- Customers are *controllers* of their data
- Think of it as a chain of responsibility

---

# Using Customer Data

- Rights governed by Data Processing Agreement (DPA)
- Allowed: Using data to deliver our service
- Allowed: Aggregated statistics (if anonymized)
- Not allowed: Everything else

---

# Sub-processors 101

- Any third-party that processes customer data
- Examples: GCP, Grafana, OpenAI
- Yes, that new SaaS tool counts too
- Grey area for tools we use for internal business processing like Pylon

---

# The 30-day Rule

- Must notify customers before new sub-processors
- 30 day notice period
- Customers can object during this time
- Can be waived with written consent

---

# Engineering Responsibilities

- Check if new tools process customer data
- Plan for the 30-day notice period
- Consider if the processor might be controversial
- Ensure Legal has reviewed the DPA

---

# AI: The Spicy Sub-processor

- Legally? Just another sub-processor
- But customers care more about AI
- Some are competitors of AI providers
- Higher scrutiny on data handling

---

# AI: What We Can Do

- Run evals on production data
- Test AI features with customer data
- Prompt-tune our models

---

# AI: What We Can't Do

- Fine-tune models on customer data
- Include customer data in prompts
- Use customer-trained models across customers

---

# Customer Questions?

- We have documentation ready
- AI data handling processes are documented
- Can disable AI processing per-customer
- Legal team is here to help

---

# Key Takeaways

- Check if tools process customer data
- Remember the 30-day notice period
- Be extra careful with AI features
- When in doubt, ask Legal
