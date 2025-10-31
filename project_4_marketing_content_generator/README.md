Objective:
Automatically generate creative and witty marketing content (product descriptions or ad copy) for products in a fictional retail company.

Approach:
This project uses a Generative AI model (google/flan-t5-large) to produce compelling marketing text based on the selected product and content type.
It demonstrates how prompt engineering can shape AI creativity and control output tone, relevance, and quality.

Key Features:

Generates two types of content:

Product Description → Focused on engaging, factual, and appealing summaries of the product.

Ad Copy → Catchy and persuasive marketing messages for campaigns or promotions.

Interactive Gradio interface — easy to test and compare outputs.

Prompt-driven generation — the model’s performance strongly depends on how well the prompt is designed.

Why Prompts Matter:
The prompt acts as the creative blueprint for the AI.
By modifying wording (e.g., adding “witty,” “persuasive,” or “friendly”), you can significantly influence tone, structure, and creativity.
Experimenting with prompts helps refine how the AI interprets brand personality and marketing goals.

Learning Value:

Understand how prompt engineering impacts generative model behavior.

Experience how Generative AI can accelerate marketing and content workflows.

Observe trade-offs between model size, cost, and output creativity.

Example:

Input	Output
Product: Running Shoes
Content Type: Ad Copy	“Step into comfort and confidence! Our Running Shoes keep your pace light and your goals in sight — perfect for every stride.”

Run the Notebook:

Open in Google Colab.

Ensure fictional_retail_products.csv exists under /content/fictional_retail_docs/.

Run all cells and interact through the Gradio UI.

Note:
All content and product data are fictional and created purely for educational demonstration.
