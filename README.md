# UChicago Masters of Science in Applied Data Science
## Final Project: Analysis of GitHub Commit Data

### Overview
This project, part of the Masters of Science in Applied Data Science program at the University of Chicago, analyzes approximately 3.5 billion rows of GitHub commit data using PySpark and Google DataProc to uncover trends and patterns in the open-source community.

### Executive Summary
**Key Findings:**
- **EDA:** Ensured precision and relevance by converting time units, normalizing time zones, and excluding pre-GitHub data.
- **Commit Activity:** Peaks mid-week, especially on Thursdays and Tuesdays, with specific spikes linked to project milestones.
- **Programming Trends:** Traditional languages like Shell, Python, C, and C++ dominate, but web languages like HTML and JavaScript are rising.
- **License Distribution:** GPL-2.0 is the most prevalent, reflecting strong open-source collaboration.

### Methodology
Utilized PySpark on Google DataProc with a structured data architecture for efficient processing. Key steps included:
- **Date Transformation and Range Confirmation:** Normalized time zones and confirmed dataset's date range.
- **Data Cleaning and Integration:** Removed unnecessary columns, combined relevant tables, and ensured data quality.

### Insights
**Commit Activity:**
- Peaks on Thursdays and Tuesdays.
- Specific weeks showed spikes in activity, aiding in resource planning.

**Programming Language Trends:**
- **2008-2013:** Shell, Python, C, C++, and Perl dominate.
- **2014-2019:** Rise of HTML and JavaScript.
- **2023:** Emergence of Go.

**License Distribution:**
- **Top Licenses:** GPL-2.0, Apache-2.0, and MIT.
- **Language Specific Trends:** GPL-2.0 is prevalent across multiple languages.

**Rapidly Growing Repositories:**
- **Languages and Technologies:** Python, JavaScript, and HTML drive growth.
- **Big Tech Influence:** Minimal presence in fastest-growing repositories.

**Data Science & AI Technologies:**
- **Primary Language:** Python dominates DS/AI projects.
- **Key Frameworks:** Rapid growth in TensorFlow and Keras, with stable usage of Scikit-learn, Spark, and Hadoop.

### Conclusion and Recommendations
AI enhances productivity but can't replace human creativity and problem-solving. Recommendations include:
- **Fostering Genuine Growth:** Avoid artificial inflation in repositories.
- **Encouraging Language Diversity and Open-Source Collaboration:** Stay updated with language and licensing trends.
- **Leveraging AI Tools:** Enhance toolkits with AI for repetitive tasks, allowing focus on strategic problem-solving.

This project highlights the power of big data platforms and cloud computing in analyzing large datasets and shaping the future of software development and data science.

**Vincent Caldwell, December 2nd, 2023**
