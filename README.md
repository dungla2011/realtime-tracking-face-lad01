**- Download Python version 3.8:**

**- Create enviroment and Run commands:**

C:\Users\pc2\AppData\Local\Programs\Python\Python38\python.exe -m venv venv

python.exe --version

#Python 3.8.0

python -m pip install --upgrade pip

pip install -r .\requirements.txt

python.exe .\demo.py

**streamlit run .\demo.py**


- Open web link, drag a video to App

![image](https://github.com/user-attachments/assets/a1e0f42e-be0a-4622-a1a2-4919140ba1f9)


**Nếu muốn sử dụng CUDA:**

pip uninstall torch torchvision
pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 -f https://download.pytorch.org/whl/torch_stable.html


