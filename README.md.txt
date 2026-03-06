# Day 2 - Prompt Engineering Exercise

## System Prompt Used


You are an expert text analyst specializing in extracting structured information from product reviews and feedback.

Your task is to analyze user input about a product or service and generate a structured JSON output containing a title, summary, sentiment, keywords, and confidence score.

Context:
The user will provide a review, feedback, or opinion about a product, service, or update. You need to extract key information and present it in a consistent, machine-readable format.



## Example 1

**User Input:**
The new update to the productivity app is impressive. The interface feels smoother and the performance has improved significantly. However, the new layout is slightly confusing at first and it took me some time to adjust. Overall, I think the update is a step in the right direction.

Model Output:
{
  "title": "Productivity App Update Improves Performance",
  "summary": "The latest update enhances performance and smoothness of the productivity app. Although the redesigned layout may initially confuse users, the overall improvements make it a positive step forward.",
  "sentiment": "positive",
  "keywords": ["productivity app", "performance improvement", "interface redesign", "user experience"],
  "confidence_score": 0.87
}


Example 2
User Input:
The customer support was terrible. I waited on hold for 45 minutes and the representative was rude and unhelpful. They couldn't solve my problem and hung up on me. Worst experience ever.
Model Output:
{
  "title": "Terrible Customer Support Experience",
  "summary": "Customer support was unacceptably poor with long wait times and rude representatives. The agent failed to resolve the issue and ended the call abruptly, resulting in a completely negative experience.",
  "sentiment": "negative",
  "keywords": ["customer support", "long wait time", "rude representative", "unresolved issue", "poor experience"],
  "confidence_score": 0.95
}


Example 3
User Input:
The battery life of this phone is average. It lasts about a day with moderate use. The camera quality is decent but not as good as competitors. Overall, it's an okay device for the price.

Model Output:
{
  "title": "Average Battery Life and Camera Quality",
  "summary": "The phone offers average battery life lasting approximately one day with moderate usage. Camera quality is decent but falls short of competitor devices, making it an acceptable option for its price point.",
  "sentiment": "neutral",
  "keywords": ["battery life", "moderate use", "camera quality", "competitor comparison", "price point"],
  "confidence_score": 0.78
}



