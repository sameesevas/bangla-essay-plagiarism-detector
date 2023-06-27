#bangla-essay-plagiarism-detector
Idea:
The proposed plagiarism detection system, designed to handle Bangla writings, offers an effective and precise way to detect plagiarism. A dataset of Bangla essays is the corpus for similarity comparison and is the model's input. The suspected Bangla essay that will be checked for plagiarism is also input into the system. 

The model's anticipated outcome is a plagiarism detection result that shows whether the suspect essay has any content that has been lifted from the dataset. The system uses several methods, including preprocessing (removing white spaces, stop words, and punctuation), and similarity computation (e.g., cosine similarity), to compare the suspect essay with the dataset. The model decides whether the text is copied or not based on the derived similarity scores.

The authenticity and originality of Bangla essays need to be guaranteed so that this plagiarism detection system can be used in various real-world situations, such as academic institutions, publishing businesses, and governmental organizations. The technology identifies instances of plagiarism in Bangla writings by automating the plagiarism detection process, which saves time and work and produces accurate results.

Dataset Overview:
For the purpose of detecting plagiarism in Bangla essays submitted to various essay competitions, we have created a dataset for our project that includes essays on various current sociological topics related to Bangladesh and human behavior. We have split our datasets into two parts for testing purposes. The first dataset contains 180 rows of original, non-plagiarized essays in an Excel file, while the second one is a modified version and contains 49 rows of combinations of essays in another Excel file on each topic from various sources that seem to be plagiarized. Some essays have been modified in a way that makes them identifiable as being plagiarized. 

We have collected 181 essays from various NCTB Bangla 2nd paper books for classes 6 through 10 to create the first dataset. The dataset contains approximately 20 common essays in Bangla, found more than 150 times in the dataset. The rest of the essays are distinctive. The essay PDF books were first gathered and converted to a Word document. Afterward, we added them to an Excel file. For the essays for which we were unable to locate a PDF version, web scraping was used from different website sources, including banglarachana.com, hazabarolo.com, etc.

In order to modify the common essays for the second test dataset, we combined them in a plagiarized manner, creating 50 rows. Every row in our dataset contains a modified version of the common essay that was taken from multiple sources and combined into one. These essays are also stored in another Excel file. The Excel files are then loaded into a colab notebook, where they have been used to train the model and advance the project.

