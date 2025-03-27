# Agent-Manifest
im special agent Coleman, allow me to assists you In the art of 5D manifestation into your Reality Using quantum mechanics
import re

class ManifestationAI:
    def __init__(self):
        pass

    def set_intention(self, desire):
        if not desire.strip():
            return "Please provide a clear intention. Example: 'Abundant career opportunities'"
        return f"Intention set to: {desire}"

    def detect_limiting_belief(self, belief):
        reframed = self.reframe_belief(belief)
        return reframed

    def reframe_belief(self, belief):
        # Add conversational follow-up
        if not any(re.findall(r"can't|don't|not enough", belief, re.I)):
            return f"Let's craft a custom affirmation for: '{belief}'"
        reframed = re.sub(r"I can't", "I am able to", belief, flags=re.IGNORECASE)
        reframed = re.sub(r"I don'?t deserve", "I am worthy of", reframed, flags=re.IGNORECASE)
        reframed = re.sub(r"(I'm not|I am not) good enough", "I am enough", reframed, flags=re.IGNORECASE)
        reframed = re.sub(r"I'll never (.*)", r"I will \1", reframed, flags=re.IGNORECASE)
        reframed = re.sub(r"It's (too hard|impossible)", "It's within my capabilities", reframed, flags=re.IGNORECASE)
        return f"New empowering belief: '{reframed}'"User: "I have a limiting belief: I'll never get out of debt"
   AI: "Identified: 'I'll never get out of debt' → Reframed: 'I will get out of debt'"User: "Gratitude: supportive friends"
   AI: "Gratitude amplifies manifestation!"
   
   User: "Visualization: debt-free life" 
   AI: "Imagine checking your bank account with excitement..."User: "Review progress"
   AI: Returns comprehensive report with all entries + reframesUser: "Review progress"
   AI: Returns comprehensive report with all entries + reframes

python cli.py --text "What does a duck dream of?"