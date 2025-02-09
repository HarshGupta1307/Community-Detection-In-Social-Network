# Community-Detection-In-Social-Network

-> Setup virtual environment and install required packages
=================================================================================
bash 
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
=================================================================================

-> Run the server and api 
=================================================================================
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
=================================================================================

-> Follow the link to access the web interface:
=================================================================================
http://127.0.0.1:8000/docs#/
=================================================================================
