# Medical-Document-Summarization
## Description
Every day, hospitals encounter thousands of patients and visitors, each presenting unique cases that need to be addressed by respective departments. This necessitates the creation and maintenance of individual records for every case, leading to an overwhelming accumulation of patient data. Therefore, the practice of summarizing patient information becomes not just a convenience, but a necessity in the field of medicine.

Clinicians are required to distill information from a myriad of sources to facilitate effective communication with their peers and deliver coordinated care. In essence, the ability to succinctly summarize medical documents plays a crucial role in not just ensuring a streamlined approach to treatment but also fostering efficient, inter-departmental communication.

In this scenario, automated summary generation becomes a tool of immense potential. It carries the promise of not only saving clinicians' time but also standardizing medical notes, mitigating the risk of medical errors, and enhancing clinical decision-making. By employing algorithms designed for medical document summarization, we can collate and distill the most relevant aspects of a patient's medical history. This capability is particularly beneficial for chronically ill patients whose medical records often span hundreds of notes. By organizing and synthesizing this data, we can significantly enhance both communication and care delivery.

## Methodology
In this project, we first conducted preprocessing on our dataset, composed of multiple discharge notes associated with each subject ID. For instance, these discharge notes may contain information such as the patient's diagnosed conditions, treatment plan, prescribed medications, and follow-up recommendations. Preprocessing might involve tasks such as cleaning the text (removing unnecessary punctuation or irrelevant information), standardizing medical terms, and sorting the notes by their relevance or chronology.
Following pre-processing, we developed an encoder-decoder architecture using Recurrent Neural Networks (RNNs) to carry out extractive summarization. In the context of an RNN, the encoder processes the input sequence (in this case, the pre-processed discharge notes) and compresses the information into a context vector. The decoder then uses this context vector to generate a sequence of outputs (the summary). The extractive aspect means the model identifies and extracts the most relevant sentences or phrases directly from the original notes, without altering their wording.

In conclusion, through preprocessing of data and subsequent utilization of an RNN-based encoder-decoder architecture, we can automate the task of summarizing medical documents. This process has the potential to significantly enhance medical practices by making patient data more manageable and accessible, ultimately leading to more effective communication, better-coordinated care, and improved patient outcomes. 

<p align="center">
  <img src="https://github.com/Sayeda-fatima/Medical-Document-Summarization/assets/86098096/79388963-6056-4cf8-9ff8-dcfba70991b0" alt="Image" />
  <br/>
  <em>Extractive Summarizer Architecture</em>
</p>

