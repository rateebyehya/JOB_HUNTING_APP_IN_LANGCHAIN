# JOB HUNTING VIRTUAL ASSISTANT USING LANGCHAIN, STREAMLIT, and HUGGING FACE

🚀🌐 A VIRTUAL ASSISTANCE TOOL FOR JOB SEEKERS USING LANGCHAIN 🚀

🌐My ninth project in Langchain, Streamlit, and HuggingFace under the mentorship of SHARATH RAJU is all about CREATING AN AI VIRTUAL ASSISTANT FOR JOB HUNTING.

🔍 PROJECT OVERVIEW: 

This tool, designed for the JOB HUNTING WEBSITE: https://jobs.excelcult.com/ , empowers users to effortlessly SEARCH for specific companies and ACCESS JOB LISTINGS WITH EASE.

💡 How It Works:

1️⃣ The GREAT LANGCHAIN "SiteMapLoader" DOCUMENT LOADER allows us to easily READ all the data from ANY WEBSITE. BeautifulSoap is then used to scrape it!

2️⃣ TEXT CHUNKS are then created from the scraped documents using LANGCHAIN's TEXT SPLITTER.

3️⃣ Texts are then transformed to EMBEDDINGS using HUGGINGFACE's Sentence Transformer Embeddings.

4️⃣ EMBEDDINGS and DOCUMENTS are then PUSHED to PINECONE, a VECTOR STORE that we use to store the data for later retrieval!

5️⃣ After the user prompts the COMPANY they would want to search for, LangChain's RETRIEVERS pull data from Pinecone and perform SEMANTIC SEARCHES, delivering LINKS for APPLICATIONS!

6️⃣ THE OUTPUT???? Comprehensive information about the company and direct links to apply for jobs from that specific website. 

🚀 THIS CAN BE SCALED TO HUNDREDS OF WEBSITE, allowing users to search for jobs in ONE SPECIFIC PLATFORM

👇 In the first figure, you can see how SiteMapLoader IN ACTION where it is reading all the website's pages. The other figures show the UI interphase on STREAMLIT and how it generates the desired output (INFORMATION about the company AND links for job applications)!! 
