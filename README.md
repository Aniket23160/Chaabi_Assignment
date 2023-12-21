# Project_CSV
The repository contains files for a chatbot to chat with provided csv file.<br />
I have createod a streamlit app and an api using fastapi to show the final processed output for the given query.<br />
Following are some of the screenshots of the working code for both streamlitapp and api:<br />
<img width="1470" alt="Screenshot 2023-11-23 at 2 11 30 AM" src="https://github.com/Aniket23160/Chaabi_Assignment/assets/43294505/7a34f67b-515d-45b1-9f5b-6b15698876c5"><br />
<img width="1470" alt="Screenshot 2023-11-20 at 10 37 37 PM" src="https://github.com/Aniket23160/Chaabi_Assignment/assets/43294505/3afb7607-67c3-470b-9fcd-065681e68f09"><br />
<img width="1470" alt="Screenshot 2023-11-20 at 9 35 17 PM" src="https://github.com/Aniket23160/Chaabi_Assignment/assets/43294505/14e294c6-d109-4751-b75a-c8c2852a7156"><br />

<br />
Steps to run:<br />
Download the files.<br />
Download llama2 model from https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin<br />
In command line write:<br />
pip install -r requirements.txt<br />
<br />
Part 1:<br />
To run streamlit app:<br />
Change the paths used in the code to your respective file paths.<br />
Streamlit run streamllitapp.py<br />
<br />
Part 2:<br />
Change the paths used in the code to your respective file paths.<br />
To run api file:<br />
uvicorn app: app –reload<br />
<br />
Note: app loading and query result processing might take sometime depending upon the system configurations.
Run code on GPU
