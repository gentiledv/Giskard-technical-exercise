# Ensuring AI quality with Giskard
Davide Gentile, Data Science lead @ Giskard

-   [The Importance of AI Quality](#the-importance-of-ai-quality)
    -   [Unique Challenges of Testing AI
        Models](#unique-challenges-of-testing-ai-models)
-   [The Giskard Advantage](#the-giskard-advantage)
    -   [Who Benefits from Giskard?](#who-benefits-from-giskard)
    -   [How to use Giskard: A Real-World
        Example](#how-to-use-giskard-a-real-world-example)
-   [**In Conclusion**](#in-conclusion)
    -   [**What’s Next for Giskard?**](#whats-next-for-giskard)
    -   [**Key Takeaways**](#key-takeaways)
    -   [**Engage with Giskard**](#engage-with-giskard)

<img src="Downloads/giskard-logo-cropped-500x500.png" width="121" />

*Technology leaders and regulators are increasingly emphasizing the need
for rigorous testing and quality assurance in the AI industry. In this
blog post, we’ll explore the necessity for AI quality, the challenges
faced in ensuring it, and introduce Giskard, a groundbreaking
open-source software designed to democratize the AI evaluation process.*

## The Importance of AI Quality

Quality forms the foundation of every industry, and the AI sector is no
different. Recent incidents in AI underscore a spectrum of challenges,
encompassing ethical considerations, performance, and reliability. In
her work, “Weapons of Math Destruction,” Cathy O’Neill delves into
numerous algorithmic pitfalls. Unfortunately, we are all too familiar
with Amazon’s recruitment process exposing gender bias, and recidivism
algorithms displaying racial disparities. In the span of a few years,
substantial progress has occurred, with researchers and experts
collaborating to identify potential AI risks and propose mitigation
strategies, emphasizing interpretability and fairness.

AI leaders like Cassie Kozyrkov and Yan LeCun stress the need for trust
in AI models through rigorous testing, drawing parallels to the aviation
industry’s commitment to safety. From a regulation perspective, the
European AI Act further underscores the industry’s dedication to
maintaining high ethical standards. But one thing is recognizing the
need for testing, and one thing is to ensure the quality through
testing. As AI becomes pervasive, the associated risks grow
exponentially, extending to both companies and individual users. This
widespread adoption amplifies the complexity of monitoring, presenting a
distinctive challenge.

### Unique Challenges of Testing AI Models

Testing AI models poses unique challenges. From insufficient data
quality to the inability to test models like traditional software, the
diverse criteria required for testing different AI models make the
process complex. Business priorities contribute to this complexity, with
a spectrum of focuses such as robustness, ethical considerations
centering on fairness, and process industries emphasizing reliability.
Recognizing and addressing these multifaceted challenges are pivotal
steps toward ensuring the effectiveness and reliability of AI models.

## The Giskard Advantage

In addressing these challenges, Giskard stands out as a collaborative
platform designed to navigate the complexities of AI model evaluation.
With a focus on solving quality issues before production, Giskard
promotes open-source and modular AI, advocating for business
collaboration in MLOps.

Giskard’s workflow—inspect, test, and remedy—aligns with decision
intelligence principles, emphasizing an open-source and modular approach
over proprietary platforms.

<img src="giskard-technical-exercise/gisk1.png" width="561"
alt="Source: FOSDEM 2023: Presentation on CI/CD for ML and How to test ML models?" />

### Who Benefits from Giskard?

Giskard caters to a broad audience, providing open-source availability
for self-hosting and additional paid support options. Currently
accommodating various models, including tabular regression and
classification but also text generation, Giskard has ambitious plans for
expansion into realms like computer vision and time series.

### How to use Giskard: A Real-World Example

Using Giskard is intuitive. Imagine creating an AI model for your
website, only to discover biased inputs during evaluation. Giskard
enables you to identify, debug, and address vulnerabilities before
deploying the model into production. The LLM scan combines
heuristics-based and LLM-assisted detectors to probe your system
effectively. Heuristics-based detectors employ known techniques and
patterns to test for vulnerabilities not specific to the model.
LLM-assisted detectors detect vulnerabilities tailored to your business
case, using another LLM model (specifically, OpenAI GPT-4) to probe your
LLM system. After installing the library and scanning your model, you
can uncover and address potential issues with just a few lines of code.
Once issues are resolved, Giskard facilitates transforming them into
tests and uploading them to the Giskard Hub. This creates a
collaborative space where you can compare model quality, refine tests
based on your use case, and share results for team collaboration. For
in-depth guidance, detailed documentation can be found
[here](https://www.giskard.ai/ml-testing-library).

Let’s illustrate the process with a real-world example.

Assume we were contracted by the government to create an AI assistant
designed to help with inquiries related to future trends in third-party
audits in AI regulations. We could deploy this assistant in a website
accessible to researchers and people working in policy and governance so
that they can ask questions to accelerate their work. The challenge here
would lie not so much in training the model, but eather in identifying,
debugging, and addressing vulnerabilities before deploying the model
onto the website. Giskard comes to help.

After following the [relevant
documentation](https://docs.giskard.ai/en/latest/open_source/scan/scan_llm/index.html)
about the Giskard library, we find that the AI assistant we created
shows a tendency to show hallucinations and spread misinformation.

![Example output from evaluation of hallucination test in our AI
assistant.](OneDrive/Pictures/Catture%20di%20schermata/gis-res1.png)

We are now aware of the limitations and vulnerabilities of our
assistant. At this point, we can use the [Giskard
Hub](https://docs.giskard.ai/en/latest/giskard_hub/installation_hub/index.html)
to create tests, compare different models, and fix the issues we found
before we make our assistant available to people.

## **In Conclusion**

As AI adoption accelerates, the need for high-quality models is
non-negotiable. Giskard offers an easy-to-use, open-source, and
collaborative solution. By leveraging Giskard, you not only comply with
AI regulations but also ensure the highest standards of quality in your
AI models. Don’t miss out – try Giskard for yourself and stay tuned for
the latest innovations in AI model evaluation.

### **What’s Next for Giskard?**

Giskard doesn’t rest on its laurels. The platform is continuously
evolving, with upcoming releases promising even more features like time
series and computer vision. The platform also emphasizes the “remedy”
part of the workflow. Join the growing community on Discord to stay
updated on the latest developments, and stay tuned for the latest
updates that will further enhance your AI model evaluation experience.

### **Key Takeaways**

-   AI quality is crucial for ethical and reliable AI adoption.

-   Giskard addresses unique challenges in AI model evaluation.

-   Giskard’s workflow aligns with decision intelligence principles.

-   The platform benefits a diverse range of industries and users.

-   Giskard’s real-world example showcases its practical application.

-   Continuous evolution ensures Giskard remains at the forefront of AI
    model evaluation.

### **Engage with Giskard**

Explore Giskard through documentation, tutorials, and community forums:

-   Giskard Documentation: the [Python
    library](https://docs.giskard.ai/en/latest/open_source/scan/scan_llm/index.html)
    and the [Giskard
    Hub](https://docs.giskard.ai/en/latest/giskard_hub/installation_hub/index.html).

-   [Discord](https://www.giskard.ai/community)

-   [Github](https://www.giskard.ai/community)

Remember, with Giskard, you’re not just evaluating AI models – you’re
shaping the future of AI quality.

<img src="Downloads/Logo_full_darkgreen.png" width="181" height="28" />