pip install virtualenv
python -m virtualenv venv
.\venv\Scripts\activate

pip install -r requirements.txt
python app.py




docker build -t jais13b .
docker run -v C:\Users\mohamed\jais-downloads\jais-original-repo:/usr/src/app/model -p 4000:80 jais13b
