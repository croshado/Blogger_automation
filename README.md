# Automated Blog Post Creation and Publishing System

This repository contains the code for an end-to-end automation system that scrapes relevant data from the web, generates SEO-optimized blog posts using **gemini-1.5-flash (Gemini)**, and automatically publishes the content to **Blogger**. The system leverages web scraping, AI-driven content generation, and browser automation to streamline the process of blog creation and publishing.

## Features
- **Web Scraping**: Uses **Tavily** for gathering relevant content from high-ranking websites based on search queries.
- **AI Content Generation**: Leverages **gemini-1.5-flash** (Gemini) to generate structured and SEO-optimized blog posts.
- **Automated Publishing**: Publishes the generated blog content directly to **Blogger** using **Selenium** for browser automation.
- **Dynamic Topic Generation**: Integrates with an **Excel sheet** to fetch new blog topics automatically, ensuring fresh content.
- **Content Optimization**: Ensures that each post follows best SEO practices with proper formatting, headings, and alt-text for images.

## Technologies Used
- **Python** for scripting and automation.
- **Selenium** for automating the Blogger interface.
- **Tavily** for web scraping.
- **gemini-1.5-flash** (Gemini) for content generation.
- **Excel** for dynamic topic management.

## Setup Instructions
1. **Clone the repository**  
   Clone the repository to your local machine:
   ```bash
   git clone <repo-link>```

2. **Install dependencies**
   Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Blogger credentials**
   To automate posting to Blogger, configure the required **Blogger credentials** for automation in the script.

4. **Prepare the Excel sheet**
   Modify the **Excel sheet** with the blog topics that you want to generate content for. The topics will be fetched automatically during the execution of the system.

5. **Run the system**
   Execute the main script to start the content generation and publishing cycle:

   ```bash
   python main_script.py
   ```
##NOTE—Please log in to your blogger in the web browser profile you will use in the code (e.g., Edge, Chrome, etc.).

## How It Works

* The system fetches topics from an **Excel sheet**.
* For each topic, it uses **Tavily** to gather relevant content from high-ranking websites.
* The content is then processed by **Gemini** to generate a structured, SEO-optimized blog post.
* Finally, **Selenium** automates the process of publishing the generated content directly to **Blogger**.

## Contributing

Feel free to fork the repository, contribute to the code, or open issues for any improvements or bugs. Pull requests are welcome.


---

*By Vinayak Pratap Rana*

```

Make sure to replace `<repo-link>` with your actual repository link in the "Clone the repository" section, and customize the steps further if needed based on your project specifics.
```
