
The Code Is Not Listening: It Is Learning From You
By: Domoa Al-Fatlawi — Cybersecurity Engineering Student
Many of us have started to treat Artificial Intelligence (AI) as a "friend" or someone who truly "understands" us. We talk to it when we are lonely or stressed, expecting a human-like connection. But as a cybersecurity student, I want to share the technical reality: AI doesn't have feelings; it has data.
1. It’s Not a Conversation, It’s an Operation
When you tell an AI how you feel, it doesn't "feel" back. It breaks your words down into numbers and looks for a pattern. It’s like a calculator that predicts words instead of sums.
Example of what happens behind the screen:
# You see: "I am sad."
# The AI sees:
input_data = "I am sad"
processed_pattern = analyze_statistics(input_data)
# It responds based on "probability," not "empathy."

2. You are Teaching the System
AI sounds so real because it is constantly learning from you. This is a process called RLHF (Reinforcement Learning from Human Feedback). Every time you share a secret or an emotion, the AI uses that interaction to "mimic" humans better in the future.
The technical cycle:
// Every interaction is a lesson for the model
function onUserMessage(message) {
    saveToTrainingData(message); // Your words become the AI's textbook
    updateModelWeights();        // The AI improves its "act"
}

3. Why This Matters for Your Privacy
Because the AI is a "learning machine" and not a "person," anything you tell it can become part of its permanent memory. In cybersecurity, we say: If you wouldn't say it in public, don't type it in a prompt. AI can be a great assistant for coding or research, but it is a risky place to store your personal emotions.
References & Realities
To understand more about how AI models are trained and their risks, you can check these official resources:
 * NIST: AI Risk Management - Why we must be careful with AI data.
 * Stanford HAI: AI vs. Human Awareness - Research on why AI isn't conscious.
 * OpenAI: How Models Learn - Explanation of the RLHF process.
Final Thought
Respect AI as a powerful tool, but never forget it is just code. It learns, it adapts, and it improves—but it doesn't care. Using it wisely is part of your digital maturity.
