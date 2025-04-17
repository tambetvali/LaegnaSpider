# Laegna Spider

Laegna Spider gathers the web of information from different sources:
- Laegna Website (implemented initially)
- User's Document collections (implemented after this)
- Other websites, where HTML access or API access, such as Notion.io, would be included.
- DataSets, such as Kaggle or Hugging Face integration to gather the datasets.

It will use LaegnaFS to gather all the data and create structured filesystem, which can be used to train and fine-tune AI or to serve as document collection; it can also use the filesystem directly.

## Functionality (later)

In addition to having a dataset, it would provide the following:
- Possibly use the Server as "other client", enabling local script support and additional generators.
- Collect user information, such as which books (name for my document collections and intgrators) they would use and specify all the parameters, such as what they want to teach to the bot, how long should be the content, how much there will be generated content etc.
- Create pages for backlinking: given some page they use with their AI, they can generate a project, which has given version of the page and allows to use Prolog sentences with Markdown files and chapters to connect their own pages to this original source; the intermediate cache is used to keep clear connection to given version. Backlink would allow the original page to include their generations, such as it might generate identic chapter structure and add something to end of each chapter, to comment or extend it (as it's a reading for humans and AI's, while the humans would garbage collect more, AI would be happy with many long sources and use more considerable amount of what is available, for example through your generator).

For an AI:
- It could provide a document collection.
- It could provide training or fine-tuning collection of Q&A cards and other supported types.

It could also directly download an AI model and train it directly on it's own, using libraries such as LitGPT and others.

# Laegna Spider: Comprehensive Data Gathering & AI Training

_CoPilot follow-up._

## Core Purpose
Laegna Spider serves as a structured data collector, integrating information from various sources to build a refined filesystem for AI training and document organization.

### Data Sources
- **Laegna Website** (initial implementation)
- **User's Document Collections** (future expansion)
- **External Websites** (HTML/API integrations, e.g., Notion.io)
- **Datasets** (Kaggle, Hugging Face, and more)

### Filesystem Integration
Utilizing **LaegnaFS**, Laegna Spider ensures gathered data is properly structured to:
- Train and fine-tune AI models.
- Serve as an interactive document collection.
- Be accessed directly for analytics or learning.

## Expanded Functionality
Beyond data collection, future features include:
- **Server Integration**: Acts as an "other client," enabling script execution and additional automation.
- **User-defined AI Training**:
  - Users specify document types, training parameters, and content generation levels.
  - AI adapts to structured learning goals.
- **Advanced Backlinking System**:
  - Users link AI-generated projects with structured Markdown using Prolog sentences.
  - Version-controlled caching maintains reference integrity.
  - AI-enhanced chapter extension enriches the reading experience.

### AI-Specific Enhancements
- **Document Collection**: Organizes structured files for AI-assisted learning.
- **Training & Fine-tuning**: Generates Q&A datasets and structured metadata.
- **Direct AI Model Training**:
  - Laegna Spider can download models and train them autonomously.
  - Libraries such as **LitGPT** enable local fine-tuning and optimized performance.

---

With these advancements, **Laegna Spider** evolves into a fully integrated AI-assisted tool for structured web intelligence, document management, and custom AI training workflows.
